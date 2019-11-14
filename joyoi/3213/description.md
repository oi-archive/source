# 
输入A和B，输出A和B的最大公因数
贪吃蛇代码：
#include <windows.h>
#include <stdlib.h>
#include <conio.h>
#include <time.h>
#include <cstring>
#include <cstdio>
#include <iostream>
#define  N 20 
using namespace std;
int gameover;
int x1, y1;
int x,y;
long long start;
class snake_position
{
	public:
	    int x,y;      
    	snake_position(){};
   		void initialize(int &);
};
snake_position position[(N-2)*(N-2)+1]; 
void snake_position::initialize(int &j)
{ 
    x = 1;
	y = j;
}
class snake_map
{
	private:
    	char s[N][N];
    	int grade, length;
    	int gamespeed; 
    	char direction; 
    	int head,tail;
    	int score;
    	bool gameauto;
	public:
    	snake_map(int h=4,int t=1,int l=4,char d=77,int s=0):length(l),direction(d),head(h),tail(t),score(s){}
    	void initialize();  
    	void show_game();
    	int updata_game();
    	void setpoint();
    	void getgrade();
    	void display();
};
void snake_map::initialize()
{
    int i,j;
    for(i=1;i<=3;i++)
        s[1][i] = '$';
    s[1][4] = '+';
    for(i=1;i<=N-2;i++)
        for(j=1;j<=N-2;j++)
            s[i][j]=' '; 
    for(i=0;i<=N-1;i++)
        s[0][i] = s[N-1][i] = '-'; 
    for(i=1;i<=N-2;i++)
        s[i][0] = s[i][N-1] = '|'; 
}
void snake_map::show_game()
{
    system("cls"); 
    int i,j;
    cout << endl;
    for(i=0;i<N;i++)
    {
        cout << '\t';
        for(j=0;j<N;j++)
            cout<<s[i][j]<<' '; 
        if(i==2) cout << "\t等级："<<grade;
        if(i==6) cout <<"\t速度："<<gamespeed/1000.0<<"s/格";
        if(i==10) cout << "\t得分："<<score<<"分";
        if(i==14) cout << "\t暂停：按一下空格键" ;
        if(i==18) cout << "\t继续：按两下空格键" ;
        cout<<endl;
    }
}
void snake_map::getgrade()
{
    cin>>grade;
    while( grade>7 || grade<1 )
    {
        cout << "请输入数字1-7选择等级，输入其他数字无效" << endl;
        cin >> grade;
    }
    switch(grade)
    {
        case 1: gamespeed = 800;gameauto = 0;break;
        case 2: gamespeed = 500;gameauto = 0;break;
        case 3: gamespeed = 400;gameauto = 0;break;
        case 4: gamespeed = 300;gameauto = 0;break;
        case 5: gamespeed = 200;gameauto = 0;break;
        case 6: gamespeed = 100;gameauto = 0;break;
        case 7: grade = 1;gamespeed = 800;gameauto = 1;break;
    }
}
void snake_map::display()
{
    cout << "\n\t\t\t\t等级：" << grade;
    cout << "\n\n\n\t\t\t\t速度：" << gamespeed/1000.0<<"s/格";
    cout << "\n\n\n\t\t\t\t得分：" << score << "分" ;
}
void snake_map::setpoint()
{
    srand(time(0));
    do
    {
        x1 = rand() % (N-2) + 1;
        y1 = rand() % (N-2) + 1;
    }while(s[x1][y1]!=' ');
    s[x1][y1]='*';
}
char key;
int snake_map::updata_game()
{
    gameover = 1;
    key = direction;
    start = clock();
    while((gameover=(clock()-start<=gamespeed))&&!kbhit());
        if(gameover)
        {
            getch();
            key = getch();
        }
        if(key == ' ')
        {
            while(getch()!=' '){};
        }
        else
            direction = key;
        switch(direction)
        {
            case 72: x= position[head].x-1; y= position[head].y;break; 
            case 80: x= position[head].x+1; y= position[head].y;break;
            case 75: x= position[head].x; y= position[head].y-1;break;
            case 77: x= position[head].x; y= position[head].y+1;
        }
        if(!(direction==72||direction==80||direction==75 ||direction==77))
            gameover = 0;
        else if(x==0 || x==N-1 ||y==0 || y==N-1)
            gameover = 0;
        else if(s[x][y]!=' '&&!(x==x1&&y==y1))
            gameover = 0;
        else if(x==x1 && y==y1)
        {
            length ++;
            if(length>=8 && gameauto)
            {

                length -= 8;
                grade ++;
                if(gamespeed==8000)
                    gamespeed -= 300;else
                if(gamespeed==500)
                    gamespeed -= 100;else
                if(gamespeed==400)
                    gamespeed -= 100;else
                if(gamespeed==300)
                    gamespeed -= 100;else
                gamespeed=100;
        	}
            s[x][y]= '+';
            s[position[head].x][position[head].y] = '$';
            head = (head+1) % ( (N-2)*(N-2) );
            position[head].x = x;
            position[head].y = y;
            show_game();
            gameover = 1;
            score += grade*20; 
            setpoint();
        }
        else
        { 
            s[position[tail].x][position[tail].y]=' ';
            tail= (tail+1) % ( (N-2) * (N-2) );
            s[position[head].x][position[head].y]='$';
            head= (head+1) % ( (N-2) * (N-2) );
            position[head].x = x;
            position[head].y = y;
            s[position[head].x][position[head].y]='@';
            gameover = 1;
        }
    return gameover;
}
int main()
{
	system("color 9f"); 
    char ctn = 'y';
    int nodead;
    cout<<"\n\n\n\n\n\n\n\n\t\t\t\t\t\t 欢迎进入贪吃蛇游戏!"<<endl;
    cout<<"\n\n\n\t\t\t\t\t\t 按任意键马上开始。。。"<<endl;
    getch();
    while( ctn=='y' )
    {
        system("cls");
        snake_map snake;
        snake.initialize();
        cout << "\n\n\t\t\t\t\t\t请输入数字选择游戏等级：" << endl;
        cout << "\n\n\n\t\t\t\t\t\t1.等级一：速度 0.8s/格 \n\n\t\t\t\t\t\t2.等级二：速度 0.5s/格 \n\n\t\t\t\t\t\t3.等级三：速度 0.4s/格 ";
        cout << "\n\n\t\t\t\t\t\t4.等级四：速度 0.3s/格 \n\n\t\t\t\t\t\t5.等级五：速度 0.2s/格 \n\n\t\t\t\t\t\t6.等级六：速度 0.1s/格 \n\n\t\t\t\t\t\t   7.自动升级模式" << endl;
        snake.getgrade();
        for(int i=1;i<=4;i++)
        {
            position[i].initialize(i);
        }
        snake.setpoint();
        do
        {
            snake.show_game();
            nodead = snake.updata_game();
        }while(nodead);
        system("cls");
        cout << "\n\n\n\t\t\t\tGameover！\n\n"<<endl;
        snake.display();
        cout << "\n\n\n\t\t    是否选择继续游戏？输入 y 继续，n 退出" << endl;
        cin >> ctn;
    }
	Sleep(100);cout<<"G";Sleep(100);cout<<"o";Sleep(100);cout<<"o";
	Sleep(100);cout<<"d";Sleep(100);cout<<"b";Sleep(100);cout<<"y";
	Sleep(100);cout<<"e";Sleep(100);cout<<"!";Sleep(100);cout<<"\n";
	cout<<"欢迎常来玩贪吃蛇！再见！\n";
    while(1); 
}# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>4 6
</td><td>2</td></tr></table>
