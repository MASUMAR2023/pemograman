# pemograman ini saya ubah dari pemateri
function filterByValue(array, string) {
    return array.filter(o =>
        Object.keys(o).some(k => o[k].toLowerCase().includes(string.toLowerCase())));
}

function robotPencariNamadepan(array,string){
    return array.filter(siswa=>
        Object.keys(siswa).some(k => siswa[k].toLowerCase().includes(string.toLowerCase())))
}
