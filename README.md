# pemograman ini saya ubah dari pemateri
function filterByValue(array, string) {
    return array.filter(o =>
        Object.keys(o).some(k => o[k].toLowerCase().includes(string.toLowerCase())));
}

function robotPencariNamadepan(array,string){
    return array.filter(siswa=>
        Object.keys(siswa).some(k => siswa[k].toLowerCase().includes(string.toLowerCase())))
}
let datadiria ={
    nama:"abdul",
    kelas:"6",
    umur:"12",
    hobi:"tidur",
    lulus:"false",
}
datadiria.nama="umar abdul";
// console.log(datadiria);

let datadirib ={
    nama:"faroz",
    kelas:"1sma",
    umur:"15",
    hobi:"ngaji",
    lulus:"false",
}
datadirib.nama="faroz";
// console.log(datadirib);

let datadiric ={
    nama:"adurrozaq",
    kelas:"4",
    umur:"10",
    hobi:"ngaji",
    lulus:"false",
}
datadiric.nama="adurrozaq";
// console.log(datadiric);

let datadirid ={
    nama:"abdullah",
    kelas:"1",
    umur:"7",
    hobi:"ngaji",
    lulus:"false",
}
datadirid.nama="abdullah";
// console.log(datadirid);

let datadirie ={
    nama:"azam",
    kelas:"4",
    umur:"10",
    hobi:"ngaji",
    lulus:"false",
}
datadirie.nama=" azam";
// console.log(datadirie);

let datadirif ={
    nama:"saad",
    kelas:"1",
    umur:"7",
    hobi:"ngaji",
    lulus:"false",
}
datadirif.nama="saad";
// console.log(datadirif);

let datadirig ={
    nama:"ubaydillah",
    kelas:"6",
    umur:"12",
    hobi:[],
    lulus:"false",
}
datadirig.nama="ubaydillah";
// console.log(datadirig);

let datadirih ={
    nama:"abdurrahman",
    kelas:"3smp",
    umur:"14",
    hobi:[],
    lulus:"false",
}
datadirih.nama="abdurrahaman";
// console.log(datadirih);

let kelas=[]

kelas.push(
     datadiria,

     datadirib,
 
     datadiric,
    
     datadirid,
    
     datadirie,
    
     datadirif,
    
     datadirig,
    
     datadirih,

)
