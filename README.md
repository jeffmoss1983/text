# text
var result ={
arr:[]
x :" "
y :" "
}
function randBd[]{
if ( result.arr.length==0){result.arr =["a","b","c","d"];
}
result.x = Math.floor(Math.random()*result.arr.length);
if(result.y == result.arr[result.x]){result.arr.splice(result.x,1);
retun arguments.callee();
}else{result.y = result.arr[result.x];
result.arr.splice(result.x,1);
return result.y;
}
};
var num = randBd();
if( num == "a"){//执行动画2
hypeDocument.showSceneNamed("1");
}else if ( nume == "b"){//执行动画3
hypeDocument.showSceneNamed("2");
}else if ( nume == "c"){//执行动画4
hypeDocument.showSceneNamed("3");
}else if ( nume == "d"){//执行动画5
hypeDocument.showSceneNamed("4");
}
Agenet.customizeEvent('Event_WECHAT_CE',null,null)
