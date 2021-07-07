# veganavscode README

this is code snipptes, highlighting and tips for vegana js development.

## Features

fast code snippets saves time formating vegana js apis.

### api snippets

majority of apis are placed in there respective subsections like get,set,wet,router

few apis are directly exposed for speed like make sub apis can be directly accessed like div,input,element,select,list etc.

navigator apis are directly exposed vis nav.sub_api ie nav.comp for engine.router.navigate.to.comp similarly nav.page,nav.cont and nav.panel are directly exposed for faster access.

router init apis are explosed via router subsection ie engine.router.init.comps is exposed via router.comps similarly router.conts and router.panels are explosed via this sub setion.

### custom snippets

a lot of code is reapeted when we check variables and return some values so there are some custom snippets provided to make development speed faster.

#### check snipets

##### check var is not false, undefined or null.

```
//input
check

//output
if(!var_name){
    work
}
```

##### check array have some items

```
//input
check.array_len

//output
if(!(var_name instanceof Array) || var_name.length === 0){
    work
}
```

##### check object have some keys

```
//input
check.object_len

//output
if(!(var_name instanceof Object) || Object.keys(var_name).length === 0){
    work
}
```

#### return snipets

##### return true

```
//input
.r

//output
return true;
```

##### return false

```
//input
.r!

//output
return false;
```

##### return value

```
//input
.rv

//output
return some_value;
```

