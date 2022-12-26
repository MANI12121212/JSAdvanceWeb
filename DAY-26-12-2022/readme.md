# Advance Javascript Class 

```
// var arr = [1,2,3,4,5,6,7,8,9,10];
// arr.map((value,index, array)=>{
//     document.write(index)
//    document.write(`${value} <br/>` );

// })

// var arr2 = ["manish","gaurav","rishabh"];
// var finalArr  = arr2.map((ele)=>{
//       return ele.toUpperCase()
// })
// document.write(finalArr);
// document.write(arr2)

// var arrOfArr = [[1,2,3,4,5,6],["Manish","Nigam"],[7,8,9,"gyan"]]

// // arrOfArr[0].map((ele)=>{
// //     document.write(ele)

// // })
// arrOfArr.map((ele)=>{
//     ele.map((Element)=>{
//         console.log(Element)
//     })

// })

var arrOfArr = [[[1,2,3]],[[4,5,6],["d","e","f"]],[[7,8,9]]]

arrOfArr.map((ele)=>{
    ele.map((ele)=>{
        ele.map((ele)=>{
            document.write(ele);
        })
    })
})


const hello = {
    name  : "manish",
    array : [1,2,3,4,5,6,7,8,9],
    age : 24,
    obj : {
        arrOfArr : [[[1,2,3,4]],[[7,8,9]]]
    }
}

hello.obj.arrOfArr.map((ele)=>{
    ele.map((ele)=>{
        ele.map((ele)=>{
            document.write(ele);
        })
    })
})
```