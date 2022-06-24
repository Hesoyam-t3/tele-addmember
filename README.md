# tele-addmember
Scrape addmember 
<hr>
Step 1: Install Telethon packagenya dulu di Vs code ya massehhh semua ada di paling bawah linknya :) <br/>
pip install telethon
<hr>
Step 2: Buat file config.json Copy file > config.json dari config.example.json.<br/>
<hr>
{<br/>
	"group_target": 1398120166, --> id group Kita<br/>
	"group_source": 1490302444, --> id group target<br/>
 	"accounts": [<br/>
		{<br/>
			"phone": "+62XXXX", <br/>
			"api_id": 1234566,<br/>
			"api_hash": "57c6f3c72c2f21676d53be2eXXXXXX"<br/>
		}<br/>
	]<br/>
}<br/>
<hr>
Step 3: Setelah itu setting  config.json yang di atas file yang kamu punya seperti nomer handphone dan api_id dan api_hash,<br/>
Copy dan jalankan kode berikut python init_session.py, masukan nomer handphone dan cek kodenya di telegram kalian dan masukan lalu enter.
<hr>
Step 4: Copy dan jalankan kode berikut python get_data.py Untuk dapatkan data userid dan groupnya
<hr>
Step 5: Cek bagian folder data dan buka bagian group, copy user_id (group kita) dan tempelkan di config.json  "group_target": 1398120166, --> id group Kita<br/>
lalu buka kembali data groupnya dan copy user_id target kita dan tempelkan di config.json "group_source": 1490302444, --> id group target Jika sudah simpan <br/>
<hr>
Step 6: Copy dan jalankan python add_member.py, akan otomatis ya dari Group source ke group target
<hr>
Note : Sebelum menjalankan perintah diatas install aplikasi yang ada di bawah,
<hr>
Install Python<br/>
Install vscode studio<br/>
exctrac to desktop file telethonnya<br/>
jika sudah buka vscodenya dan buka open folder arahkan ke desktop buka folder telethonnya dan oke<br/>
ikuti step 1, dan buka terminal(CMDNYA VSCODE) bagian bar atas vscodenyadan selanjutnya ikuti step 2,
setting Phone,api_id dan api hash cara mendapatan api_id dan api_hash itu kalian bisa ke : https://my.telegram.org/auth<br/>
isi datanya kya nama app pilih android/browser ya lalu ikuti stepnya sesuai dengan step 3 - step 5,<br/>
step 6 tinggal ikuti saja
<hr>
Jika sudah 30-35 members --> Tunggu 15 minutes dan ganti nomer yang akan kita korbankan 
<hr>

File :<br/>
⚫Download Python: https://www.python.org/downloads/<br/>
⚫Download VS Code: https://code.visualstudio.com/download


