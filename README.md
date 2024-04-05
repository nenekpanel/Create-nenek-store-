SC NENEK V8
BASE : HW MODS
RECODE : THOMZ
CREACOT : NENEK
*/

const fs = require('fs')
const chalk = require('chalk')

global.owner = "6288268243874"
global.namabot = "NENEK-BOTZ"
global.botname = "NENEK-BOTZ"
global.autoJoin = false
global.thumb = fs.readFileSync("./all/image/foto.jpg")
global.codeInvite = "FwtMxovJqW3Jj55x524hjT"
global.sessionName = 'sesthomz' //Gausah Juga
global.save = "NENEK"
global.tekspushkon = ""
global.tekspushkonv2 = ""
global.packname = ""
global.author = "Sticker By NENEK STORE"
global.author = "Sticker By MENEK STORE"

global.namastore = "LUXX "
global.qris = fs.readFileSync("./all/image/qris.jpg")
global.nodana = "083166461466"
global.nogopay = "083166461466"
global.noovo = "083166461466"


const mess = {
   wait: "Tunggu Bang Lagi Saya Proses",
   success: "sukses✅ PUSH KONTAK",
   save: "𝕊𝕌𝕂𝕊𝔼𝕊 𝕊𝔸𝕍𝔼 ℕ𝕆𝕄𝔼ℝ 𝕆𝕋𝕆𝕄𝔸𝕋𝕀𝕊",
   on: "Sudah Aktif", 
   off: "Sudah Off",
   query: {
       text: "Teks Nya Mana Kak?",
       link: "Link Nya Mana Kak?",
   },
   error: {
       fitur: "Mohon Maaf Kak Fitur Eror Silahkan Chat Developer Bot Agar Bisa Segera Diperbaiki",
   },
   only: {
       group: "Fitur Nya Cuman Bisa Di Dalem Grup Yah Bang",
       private: "Di Chat Pribadi nenek store Biar Bisa Di Pake",
       owner: "Ga Usah Pake Fitur Ini Asu Lu Bukan nenek store",
       admin: "Ga Usah Pake Fitur Ini Asu Lu Bukan nenek store",
       badmin: "Maaf Kak Kaya Nya Kakak Tidak Bisa Menggunakan Fitur Ini Di Karenakan Bot Bukan Admin Group",
       premium: "Maaf Kamu Belum Jadi User Premium Untuk Menjadi User Premium Silahkan Beli Ke Owner Dengan Cara Ketik .owner",
   }
}

global.mess = mess
//=================================================//
//Gausah Juga
global.limitawal = {
    premium: "Infinity",
    free: 100
}
//=================================================//
let file = require.resolve(__filename)
fs.watchFile(file, () => {
	fs.unwatchFile(file)
	console.log(chalk.redBright(`Update'${__filename}'`))
	delete require.cache[file]
	require(file)
})
