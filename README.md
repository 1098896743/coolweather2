# coolweather2
开发过程中的严重bug ：
1 对返回的数据进行解析的时候 应该按“,”解析 写成了按“.”号解析
2 从数据库中加载数据时 应该 不要忘记了从数据库中取出东西的时候 要用到list.add（）
添加到函数中去

2015年4月14日23:09:35

3 开发过程中在weatherActivity 各个控件获取相应的资源id时
//		temp1Text = (TextView)findViewById(R.id.temp1);
//		temp1Text = (TextView)findViewById(R.id.temp2);

cityNameText = (TextView) findViewById(R.id.action_set);
这两个错误 浪费时间3个小时
//不同的类中相同的方法 一点问题都没有！