#include<iostream>
#include<string>
using namespace std;
int main()
{
    string program[20] = {
        "#include<iostream>",
        "#include<string>",
        "using namespace std;",
        "int main()",
        "{",
        "    string program[20] = {",
        "    };",
        "    char inv=34;",
        "    for(int i=0;i<6;i++)",
        "        cout<<program[i]<<endl;",
        "    for(int i=0;i<19;i++)",
        "        cout<<program[18]<<inv<<program[i]<<inv<<program[19]<<endl;",
        "    cout<<program[18]<<inv<<program[19]<<inv<<endl;",
        "    cout<<program[6]<<endl;",
        "    for(int i=7;i<18;i++)",
        "        cout<<program[i]<<endl;",
        "    return 0;",
        "}",
        "        ",
        ","
    };
    char inv=34;
    for(int i=0;i<6;i++)
        cout<<program[i]<<endl;
    for(int i=0;i<19;i++)
        cout<<program[18]<<inv<<program[i]<<inv<<program[19]<<endl;
    cout<<program[18]<<inv<<program[19]<<inv<<endl;
    cout<<program[6]<<endl;
    for(int i=7;i<18;i++)
        cout<<program[i]<<endl;
    return 0;
}
