==判断等于，！=判断不等于。
a=b=c相当于A表示后面判断的是否正确
！逻辑非   &&逻辑与  ‖逻辑或 
真&&真=真  真‖真=真  真&&假=假
真‖假=假   假&&假=假 
即联结if语句可以只有if没有else
设计一个成绩判定系统，十为满分， 7~9为优秀， 6分为及格， 0~5是不及格，输入其他分数显示成绩输入有误 
int main{printf（“请输入你的成绩：”）
scanf（“%d”，&num”）
switch（num）}
case0；case1；case2；case3；case4；case5
printf（“您的成绩不合格”）
break
case6
printf（“您的成绩合格。”）
break
case7case8case9
printf（“您的成绩优秀。”）break
case10
printf（“您的成绩满分。”）
break
default
printf（“您的成绩输入有误。”）
