<html>

<head>
    <title>FORM JOIN</title>
<style>
    b {
    font-size: 30px;
    border: 2px;
    color: rgb(2, 2, 24);
}

h1 {
    color: rgb(222, 20, 20);
    font-size: 50px;
    border: 2px;
    text-align: center;
    font-family: "licida handwriting", cursive;
}

h2 {
    color: rgb(178, 26, 127);
    font-size: 30px;
    border: 2px;
    text-align: center;
    font-family: "papyrus", fantasy;
}
h3 {
       font-size: 30px;
       border: 2px;
       font-family:'Courier New', Courier, monospace
}
.L1 {
    background-color: rgb(180, 229, 245);
}

.L2 {
    background-color: rgb(236, 209, 232);
}

.T1 {
    background-color: rgb(234, 200, 206);

}

.T2 {
    background-color: rgb(234, 237, 196);
}

.T3 {
    background-color: rgb(178, 222, 202);
}
ul.a {
    list-style-type: square;
    background: #ff9999;
    padding: 20px;
}
ul li {background: #ffe5e5;
color: darkred;
padding: 5px;
margin-left: 35px;
}

a:visited {
    color: green;
}

a:hover {
    color: hotpink;
}

a:active {
    color: blue;
} 

</style>
</head>

<body>

    <image src="welcome.png" width="100%">
        <h1>WELCOME TO OUR COMMUNITY</h1>
        <h2>If you want to continue learn about fungsi and explore more about math, please join with us!!!!</h2>
        <h2>complete the form below and create your account</h2>
        <fieldset class="L1">
            <fieldset class="T1">
                <legend><b>DATA DIRI</b></legend>
             
                    <tr>
                        <td> <label for="NAMA">NAMA :</label> </td>
                        <td> <input type="text " id="nama" name="nama"></td>
                    </tr>
                    <tr>
                        <td><label for="ttl">TANGGAL LAHIIR :</label></td>
                        <td><input type="date" id="ttl" name="ttl"></td>
                    </tr>
                    <tr>
                        <td> JENIS KELAMIN : </td>
                        <td> <input type="radio" id="jk" name="lk">laki-laki</td>
                    </tr>
                    <tr>
                        <td></td>
                        <td> <input type="radio" id="pr" name="pr">wanita</td>
                    </tr>
                    <tr>
                        <td> JENJANG PENDIDIKAN : </td>
                        <td> <input type="radio" id="SD" name="SD">SD (SEKOLAH DASAR)</td>
                    </tr>
                    <tr>
                        <td></td>
                        <td> <input type="radio" id="SMP" name="SMP">SMP (SEKOLAH MENENGAH PERTAMA)</td>
                    </tr>
                    <tr>
                        <td></td>
                        <td> <input type="radio" id="SMA" name="SMA">SMA (SEKOLAH MENENGAH ATAS)</td>
                    </tr>
                    <tr>
                        <td></td>
                        <td> <input type="radio" id="SMK" name="SMK">SMP (SEKOLAH MENENGAH KEJURUAN)</td>
                    </tr>
                    <tr>
                        <td>AGAMA :</td>
                        <td> <select name="agama" id="agama">
                                <option value="#">--pilih salah satu--</option>
                                <option value="ISLAM">ISLAM</option>
                                <option value="KRISTEN">KRISTEN</option>
                                <option value="KATOLIK">KATOLIK</option>
                                <option value="BUDHA">BUDHA</option>
                                <option value="HINDU">HINDU</option>
                                <option value="KONGHUCU">KONGHUCU</option>
                            </select>
                    </tr>

                    <tr>
                        <td> HOBI :</td>
                        <td> <input type="checkbox">membaca</td>
                    <tr>
                        <td></td>
                        <td> <input type="checkbox">menulis</td>
                        </td>
                    </tr>
                    <tr>
                        <td></td>
                        <td> <input type="checkbox">menonton</td>
                    </tr>
                    <tr>
                        <td></td>
                        <td> <input type="checkbox">memasak</td>
                    </tr>
                    <tr>
                        <td></td>
                        <td> <input type="checkbox">memancing</td>
                    </tr>
                    <tr>
                        <td></td>
                        <td> <input type="checkbox">bernyayi</td>
                    </tr>
                    <td><label for="hp">NO.HP :</label></td>
                    <td><input type="tel" id="hp" name="phone" placeholder="1122-3344-5566"></td>
                    <tr>
                        <td><label for="alamat">ALAMAT :</label></td>
                        <td>

                            <textarea name="alamat" id="alamat">--isi alamat--</textarea>
                            </textarea>
                        </td>
                    </tr>
                    <tr>
                        <td><label for="photo">PAS FOTO* :</label></td>
                        <td><input type="file" id="photo" name="pp"></td>
                        </tr>
                        <tr>
                        <td><h4>*foto bebas ukuran 4x6</h4></td>
                    </tr>
             
            </fieldset>
            <fieldset class="T2">
                
                    <legend><b>DATA SEKOLAH</b></legend>
                    <tr>
                        <td> <label for="sekolah">nama sekolah :</label> </td>
                        <td> <input type="text " id="sekolah" name="ns"></td>
                    </tr>
                    <tr>
                        <td> status sekolah : </td>
                        <td> <input type="radio" id="n" name="n">negri</td>
                    </tr>
                    <tr>
                        <td></td>
                        <td> <input type="radio" id="s" name="s">swasta</td>
                    </tr>
                    <tr>
                        <td>provinsi :</td>
                        <td> <select name="prov" id="prov">
                                <option value="#">--pilih salah satu--</option>
                                <option value="ISLAM">ACEH</option>
                                <option value="KRISTEN">SUMATRA UTARA</option>
                                <option value="KATOLIK">SUMATRA BARAT</option>
                                <option value="BUDHA">SUMATRA SELATAN</option>
                                <option value="HINDU">RIAU</option>
                                <option value="KONGHUCU">KEPULAUAN RIAU</option>
                                <option value="HINDU">BENGKULU</option>
                                <option value="HINDU">LAMPUNG</option>
                                <option value="HINDU">BANGKA BELITUNG</option>
                                <option value="HINDU">KALIMANTAN BARAT</option>
                                <option value="HINDU">KALIMANTAN TIMUR</option>
                                <option value="HINDU">KALIMANTAN UTARA</option>
                                <option value="HINDU">KALIMANTAN TENGAH</option>
                                <option value="HINDU">KALIMANTAN SELATAN</option>
                                <option value="HINDU">BANTEN</option>
                                <option value="HINDU">DKI JAKARTA</option>
                                <option value="HINDU">JAWA BARAT</option>
                                <option value="HINDU">JAWA TENGAH</option>
                                <option value="HINDU">JAWA TIMUR</option>
                                <option value="HINDU">DI YOGYAKARTA</option>
                                <option value="HINDU">BALI</option>
                                <option value="HINDU">NTT</option>
                                <option value="HINDU">NTB</option>
                                <option value="HINDU">GORONTALO</option>
                                <option value="HINDU">SULAWESI BARAT</option>
                                <option value="HINDU">SULAWESI TENGAH</option>
                                <option value="HINDU">SULAWESI TENGGARA</option>
                                <option value="HINDU">SULAWESI UTARA</option>
                                <option value="HINDU">SULAWESI SELATAN</option>
                                <option value="HINDU">MALUKU UTARA</option>
                                <option value="HINDU">MALUKU</option>
                                <option value="HINDU">PAPUA</option>
                                <option value="HINDU">PAPUA BARAT</option>
                                <option value="HINDU">PAPUA TENGAH</option>
                                <option value="HINDU">PAPUA PRGUNUNGAN</option>
                                <option value="HINDU">PAPUA SELATAN</option>
                                <option value="HINDU">PAPUA BARAT DAYA</option>
                            </select>
                    </tr>
                    <tr>
                        <td> <label for="kk">kota/kabupaten :</label> </td>
                        <td> <input type="text " id="kk" name="kk"></td>
                    </tr>
                    <tr>
                        <td><label for="alamat">ALAMAT :</label></td>
                        <td>

                            <textarea name="alamat" id="alamat">--isi alamat--</textarea>
                            </textarea>
                        </td>
                    </tr>
                
            </fieldset>
            <fieldset class="T3">
                <legend><b>AKUN</b></legend>
                
                    <tr>
                        <td>
                            <lebel for="email">EMAIL :</lebel>
                        </td>
                        <td><input type="email" id="email" name="email"></td>
                    </tr>
                    <tr>
                        <td> <label for="pass">PASSWORD :</label> </td>
                        <td> <input type="password" id="pass" name="password"></td>
                    </tr>
                    <tr>
                        <td> <label for="konfpass">KONFIRMASI PASSWORD :</label> </td>
                        <td> <input type="password" id="konfpass" name="konfirmasipassword"></td>
                    </tr>

                
            </fieldset>
        </fieldset>
        </fieldset>
        
        <ul class="a">
            <h3>contac us:</h3>
            <li><a href="https://wa.me/qr/FXTPQPGMRLEKP1">WHATSUP </a></li>
            <li><a href="https://www.instagram.com/putriindriyatno?utm_source=qr">INSTAGRAM</a></li>
        </ul>
        <br>
        <button type="submit">daftar</button>
        <button type="reset">reset</button>


</body>

</html>
