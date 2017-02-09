## DOM库
        //makeArray:类数组转数组
        makeArray:makeArray,
        //jsonParse:把JSON格式的字符串转为JSON格式的数据（对象）
        jsonParse:jsonParse,
        //win:处理浏览器盒子模型的兼容性
        win:win,
        //offset:求盒子模型到body的偏移量
        offset:offset,
        //rnd:求[n,m]之间的随机整数
        rnd:rnd,
        //getByClass:限定范围 的通过 class 来 获取元素
        getByClass:getByClass,
        //hasClass:判断 元素的className上 是否包含 某个class名'box1'；
        hasClass:hasClass,
        //addClass:如果元素的className上没有某个class名，才会添加该class名；
        //'box1 box2 box3'
        addClass:addClass,
        //removeClass:判断一个元素的class上是否有某个class名，如果有干掉他；
        removeClass:removeClass,
        //getCss:获取元素的非行间样式；
        getCss:getCss,
        //setCss:给元素的某个属性，设置一个样式
        setCss:setCss,
        //setGroupCss:给元素设置一组样式 {width:xxx,height:xxx}
        setGroupCss:setGroupCss,
        //css:getCss(curEle,attr)  setCss(curEle,attr,value) setGroupCss(curEle,opt)
        css:css,
        //getChildren:获取当前元素下的所有子元素，帅选出某个标签的元素集合；
        getChildren:getChildren,
        //prev:获取当前元素的上一个哥哥元素；
        prev:prev,
        next:next,
        //prevAll:获取当前元素所有的哥哥元素
        prevAll:prevAll,
        //nextAll:获取当前元素的所有弟弟元素
        nextAll:nextAll,
        //sibling:当前元素的相邻元素 prev+next
        sibling:sibling,
        //siblings:所有的兄弟元素 prevAll+nextAll;
        siblings:siblings,
        //index:求当前元素的索引
        index:index,
        //firstChild:求当前容器下第一个子元素
        firstChild:firstChild,
        //lastChild:求当前容器下最后一个子元素
        lastChild:lastChild,
        appendChild:appendChild,
        //prependChild:如果有第一个子元素，插入到第一个子元素的前面，否则，直接插入容器的末尾；
        prependChild:prependChild,
        insertBefore:insertBefore,
        //insertAfter:如果指定元素的弟弟元素存在的话，插入到弟弟元素的前面，否则，直接插入到容器的末尾；
        insertAfter:insertAfter
