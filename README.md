# Html-Popup-Panel
<doctype html>
    <html lang="tr">
    
    <head> 
        <meta charset ="utf_8">
         <title>Tablo</title>
        <link rel="stylesheet" href="./tablo.css" type="text/css" />
    </head>

    <body>
        <div class="container">
          
        
            
            
        <table class="table">
            <tr class="tr">
                <th class="th header" colspan="4">STOK TABLO </th>
            </tr>
                

            
            <tr class="tr">
                
                <th class="th">ID</th>
                <th class="th">ÜRÜN ADI</th>
                <th class="th">STOKTAKİ ADET</th>
                <th class="th">...</th>
            </tr>

            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>
            </tr>

            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>

            </tr>

            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>

            </tr>
            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>
            </tr>
            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>

            </tr>

            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>

            </tr>
            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>
            </tr>
            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>

            </tr>

            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>

            </tr>
            <tr class="tr" >
                <td class="td">789</td>
                <td class="td">salcano</td>
                <td class="td">478</td>
                <td><button class="update" onclick="openPopup()">Güncelle</button></td>
            </tr>
            </table>
           

        </div>

        <div class="popup-container">
            <div class="popup-content"> 
                
                
                <form class="form-container">
                    <span class="close" onclick="closePopup()">&times;</span>
                    <h2 class="header-popup">Güncelleme Ekranı</h2>
                    


                    <label class="items"><b>Çalışan İsim:</b></label>
                    <input class="input-popup" type="text"  required>
        
                    <label class="items"><b>Çalışan Soyisim:</b></label>
                    <input class="input-popup" type="text"  required>

                    <label class="items"><b>Çalışan Ücreti </b></label>
                    <input class="input-popup" type="text"  required>
        
                    
                    <button class="update update-popup"> Güncelle </button>

                </form>
                
                
                
                
               
                


            </div>
        </div>

    </body>
