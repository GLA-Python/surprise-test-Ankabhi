[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6735745&assignment_repo_type=AssignmentRepo)
# batch21-22
Assignment Surprise test
def listing(num):
    lst=[]
    i = 0
    while i < len(num):
        count = 1
        while i+1 < len(num) and num[i]==num[i+1]:
            i += 1 
            count += 1 
        lst.append(str(count)+num[i])
        i += 1 
    return ''.join(lst)
z=1
n=int(input())
for i in range(n):
    print(z)
    z=listing(str(z))
