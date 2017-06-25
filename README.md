# myPickerManage 多级联动
#使用方法
```
        $('div').myPickerManage({
          //中国地址三级联动
        	//SelectDataSource:'china',//当为地址三级联动时，SelectDataSoure可以缺失
        	// placeholder:['---省---','---市---','---区---'],
        	// defaultSelect:['北京','北京市','东城区']
        	
          //三级联动
        	SelectDataSource: [{"北京": [{"x": [{"123":['fuck123']}, {"sss":['fucksss']}] },{"Y": [{"456":['4']}, {"AAA":['5']}] }]}],
        	placeholder:['---省---','---市---','---区---','---县---'],
        	defaultSelect:['北京','x','123','fuck123']
          
          //二级联动
        	// SelectDataSource: [{"北京": ['gg', "ssssss"]}, {"广东省": ["深圳"]}],
        	// placeholder:['---省---','---市---'],
        	// defaultSelect:['山西','太原市']
          
          //一级联动
        	// SelectDataSource:['男','女'],
        	// placeholder:['---性别---'],
        	// defaultSelect:['男']
        })
```
