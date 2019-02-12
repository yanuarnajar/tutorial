
var jml = 10;
var no = 1;
var salah = 6;

for( no; no <= jml; no++) {
    if ( no <= salah && no !== 5){
        console.log("hasil " + no + " benar" );
    } else if( no === 8 || no === 10 || no === 5) {
        console.log(" hasil " + no + " gagal");
    }else{
        console.log("hasil " + no + " salah");
    }
}
