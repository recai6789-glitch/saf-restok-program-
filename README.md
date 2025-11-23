[1-tum_dosyalar_birlestirilmis.txt](https://github.com/user-attachments/files/23696804/1-tum_dosyalar_birlestirilmis.txt)
*** BAŞLANGIÇ: 1-a_giris.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Giriş</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Arial', sans-serif; }
    body {
      background: linear-gradient(135deg, #e0e7ff, #c7d2fe);
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }
    .login-box {
      width: 400px;
      background: white;
      border-radius: 16px;
      padding: 40px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      text-align: center;
    }
    .logo {
      font-size: 48px;
      color: #4f46e5;
    }
    .logo::before {
      content: "💎";
    }
    .title {
      font-size: 24px;
      font-weight: 800;
      color: #4f46e5;
      margin-bottom: 24px;
    }
    .form-group {
      margin-bottom: 20px;
    }
    .form-group label {
      display: block;
      text-align: left;
      margin-bottom: 6px;
      font-weight: 600;
      color: #374151;
    }
    .form-group input {
      width: 100%;
      padding: 12px;
      border: 1px solid #cbd5e1;
      border-radius: 8px;
      font-size: 16px;
    }
    .btn-login {
      width: 100%;
      padding: 14px;
      background: #4f46e5;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
    }
    .footer {
      margin-top: 24px;
      font-size: 12px;
      color: #6b7280;
    }
  </style>
</head>
*** SON: 1-a_giris.txt ***

*** BAŞLANGIÇ: 1-ana_ekran_dolgun.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Ana Ekran</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body {
      background: #e0e7ff;
      padding: 24px;
    }
    .container {
      width: 21cm;
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 32px;
    }
    .logo {
      font-size: 26px;
      font-weight: 800;
      color: #1e3a8a;
      display: flex;
      align-items: center;
      gap: 8px;
    }
    .logo::before {
      content: "💎";
      font-size: 28px;
    }
    .status-icons {
      display: flex;
      gap: 12px;
    }
    .small-module btn-ceksenet" onclick="window.location.href='cek_senet_giris.html'">
        <div class="title">Çek-Senet</div>
        <div class="desc">Vade ve Risk Takibi (R13)</div>
      </div>
      <div class="small-module btn-envanter" onclick="window.location.href='ambar_islem_giris.html'">
        <div class="title">Ambar Yönetimi</div>
        <div class="desc">Transfer / Sayım (R14)</div>
      </div>
      
      <div class="small-module btn-ebelge" onclick="window.location.href='e_belge_yonetimi.html'">
        <div class="title">E-Belge Takip</div>
        <div class="desc">E-Fatura / E-Arşiv (R15)</div>
      </div>
      
      <div class="small-module btn-devir" onclick="window.location.href='devir_islemleri.html'">
        <div class="title">Devir İşlemleri</div>
        <div class="desc">Yeni yıla geçiş</div>
      </div>
      
      <div class="small-module btn-sistem-ayarlari" onclick="window.location.href='sistem_ayarlari.html'">
        <div class="title">Sistem Ayarları</div>
        <div class="desc">Yetkilendirme / Şirket Bilgileri</div>
      </div>
      
      <div class="small-module btn-k...
*** SON: 1-ana_ekran_dolgun.txt ***

*** BAŞLANGIÇ: 1-stok_kartı_tuslar_f2_.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Stok Kartı</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body {
      background: #f0f7ff;
      padding: 16px;
    }
    .container {
      width: 20.5cm;
      min-height: 29.7cm;
      background: white;
      margin: 0 auto;
      padding: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }

    /* ÜST BÖLÜM */
    .top-section {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
      margin-bottom: 20px;
      flex-wrap: wrap;
    }

    /* TUŞLAR – KÜÇÜKTEN BÜYÜĞE */
    .f-buttons {
      display: flex;
      gap: 8px;
      flex-wrap: wrap;
    }
    .btn {
      padding: 8px 12px;
      118">
      </div>
      <div class="form-group">
        <label class="label-alisfiyat">Alış Fiyatı</label>
        <input type="text" value="85,00 TL">
      </div>
      <div class="form-group">
        <label class="label-satisfiyat">Satış Fiatı</label>
        <input type="text" value="1.200,00 TL">
      </div>
      <div class="form-group">
        <label class="label-webgrup">Web Grup</label>
        <input type="text" value="Otomotiv">
      </div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Safire Stok Programı v2.2 – İyi Çalışmalar! 💙
    </div>

    <div class="record-copy">
      Kayıt Adı: STK-2025-000123 | Oluşturulma: 10.11.2025 | Ahmet (PC)
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("Yeni stok kartı"); }
      if (event.key === "F3") { event.preventDefault(); window.print(); }
      if (event.key === "F4") { event....
*** SON: 1-stok_kartı_tuslar_f2_.txt ***

*** BAŞLANGIÇ: 2-cari_kartı_dolgun.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Cari Kart</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body {
      background: #f0f7ff;
      padding: 16px;
    }
    .container {
      width: 20.5cm;
      min-height: 29.7cm;
      background: white;
      margin: 0 auto;
      padding: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }

    /* TUŞLAR – SADECE EKRANDA */
    .no-print,
    .no-print * {
      display: none !important;
    }
    @media print {
      .no-print,
      .no-print * {
        display: none !important;
      }
      .container {
        margin: 0;
        padding: 0;
        width: 100%;
        box-shadow: none;
        border-radius: 0;
      }
      @page {
        size: A4;
        margin: 1cm;
      }
      ılmaz">
      </div>
      <div class="form-group">
        <label class="label-tur">Cari Türü</label>
        <select>
          <option>Alıcı</option>
          <option>Satıcı</option>
          <option>Alıcı ve Satıcı</option>
        </select>
      </div>
      <div class="form-group">
        <label class="label-bakiye">Bakiye (TL)</label>
        <input type="text" value="41.500,00" readonly>
      </div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Safire Stok Programı v2.2 – İyi Çalışmalar! 💙
    </div>

    <div class="record-copy">
      Kayıt Adı: CR-2025-000123 | Oluşturulma: 10.11.2025 | Ahmet (PC)
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("Yeni cari kartı"); }
      if (event.key === "F3") { event.preventDefault(); window.print(); }
      if (event.key === "F4") { event....
*** SON: 2-cari_kartı_dolgun.txt ***

*** BAŞLANGIÇ: 3-fatura_alis.txt+.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Alış Faturası (Çoklu Çıktı)</title>
  <style>
    /* ... (CSS İrsaliye kodu ile AYNI) ... */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    body { background: #f0f7ff; padding: 16px; transition: all 0.2s; } 
    .container {
      width: 20.5cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 20px 30px; 
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      transition: all 0.2s;
    }
    
    /* TUŞLAR ve SEÇENEK KUTUSU STİLLERİ */
    .no-print { display: block; margin-bottom: 15px; }
    .f-buttons { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 10px; position: relative;}
    .btn { padding: 8px 12px; border-radius: 8px; font-weight: ...Rows; i++) {
                const emptyRow = tableBody.insertRow();
                emptyRow.className = 'empty-row';
                emptyRow.innerHTML = `<td></td><td></td><td></td><td></td><td></td><td></td><td></td><td class="row-actions no-print"></td>`;
            }
        }
    }
    
    function showPrintOptions() { document.getElementById('printOptionsBox').style.display = document.getElementById('printOptionsBox').style.display === 'flex' ? 'none' : 'flex'; }
    function setPrintFormat(format) {
        document.body.classList.remove('print-a4', 'print-a5', 'print-continuous', 'print-pdf');
        document.body.classList.add(`print-${format === 'pdf' ? 'a4' : format}`);
        document.getElementById('printOptionsBox').style.display = 'none';
        window.print(); 
    }

    function kaydet() { alert("Alış Faturası Kaydedildi. Stok Girişi ve Cari hareket gerçekleşti."); }

    window.onload = function() {
        addRow('STK100', 'PARCA-001', 'Amortisör Ön Seti', 5, 'ADET', 850.00);
        addRow('STK200', 'PARCA-002', 'Yağ Filtresi', 50, 'ADET', 50.00);
        fillEmptyRows();
    }
    
    document.addEventListener("keydown", function(event) {
...
*** SON: 3-fatura_alis.txt+.txt ***

*** BAŞLANGIÇ: 3-fatura_irsaliye_giris.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Fatura / İrsaliye Giriş Ekranı</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      height: 95vh;
    }
    
    /* TUŞLAR */
    .top-buttons { display: flex; gap: 8px; margin-bottom: 15px; flex-wrap: wrap; }
    .btn { padding: 8px 12px; border-radius: 6px; font-weight: 600; font-size: 13px; cursor: pointer; border: none; position: relative; transition: background 0.2s; }
    .btn-f2 { background: #2563eb; color:... '#2563eb';
            grandTotal.classList.remove('grand-total');
            grandTotal.classList.add('alis-total');
        } else {
            // SATIŞ/ÇIKIŞ (Yeşil Ton)
            titleElement.style.color = '#059669';
            selectElement.classList.remove('alis-style');
            tableHeader.style.backgroundColor = '#059669';
            grandTotal.classList.remove('alis-total');
            grandTotal.classList.add('grand-total');
        }
    }

    // Kısayollar
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Yeni Fatura/İrsaliye kaydı başlatılıyor."); }
      if (event.key === "F4") { event.preventDefault(); alert("F4: Cari veya Stok Kartı Arama Ekranı açılıyor."); }
      if (event.key === "F5") { event.preventDefault(); alert("F5: Fatura/İrsaliye kaydı veritabanına işleniyor (Kaydet)."); }
      if (event.key === "F6") { event.preventDefault(); alert("F6: Belge Yazdırma Önizlemesine gönderiliyor."); window.print(); }
      if (event.key === "F10") { event.preventDefault(); alert("F10: Ekran kapatılıyor."); }
    });
    
    // İşlem Türü değişikliğini dinle
    document....
*** SON: 3-fatura_irsaliye_giris.txt ***

*** BAŞLANGIÇ: 3-fatura_satis.txt ***
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Safire Stok Programı - Satış Faturası</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body {
      background: #fef2f2;
      padding: 20px;
    }
    .container {
      max-width: 1200px;
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 10px;
    }

    .top-buttons {
      display: flex;
      gap: 10px;
      margin-bottom: 24px;
      flex-wrap: wrap;
    }
    .btn {
      padding: 8px 16px;
      border-radius: 8px;
      font-weight: 600;
      font-size: 13px;
      cursor: pointer;
      border: none;
      position: relative;
      transition: all 0.3s;
    }
    ...}
      if (event.key === "F7") { event.preventDefault(); excelVeriAl(); }
      if (event.key === "F9") { event.preventDefault(); tahsilatEkle(); }
      if (event.key === "F10") { event.preventDefault(); raporla(); }
    });

    function yeniFatura() {
      if (confirm('Yeni fatura oluşturulsun mu?')) {
        alert('Yeni fatura oluşturuldu. Bilgileri girebilirsiniz.');
      }
    }

    function yazdir() {
      window.print();
    }

    function cariSec() {
      const cariKodu = prompt('Cari kodunu girin:');
      if (cariKodu) {
        alert(`Cari seçildi: ${cariKodu}\nCari bilgileri yükleniyor...`);
      }
    }

    function sil() {
      if (confirm('Bu faturayı silmek istediğinizden emin misiniz?')) {
        alert('Fatura silindi.');
        window.location.href = 'ana_ekran.html';
      }
    }

    function barkodOku() {
      const barkod = prompt('Barkod numarasını girin veya okutun:');
      if (barkod) {
        alert(`Barkod okundu: ${barkod}\nÜrün bilgileri getiriliyor...`);
      }
    }

    function excelVeriAl() {
      alert('Excel\'...
*** SON: 3-fatura_satis.txt ***

*** BAŞLANGIÇ: 4-irsaliye_alis.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Alış İrsaliyesi (Çoklu Çıktı)</title>
  <style>
    /* 1. GENEL TASARIM VE A4 DÜZENİ */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    body { background: #f0f7ff; padding: 16px; transition: all 0.2s; } 
    .container {
      width: 20.5cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 20px 30px; 
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      transition: all 0.2s;
    }
    
    /* TUŞLAR ve SEÇENEK KUTUSU STİLLERİ */
    .no-print { display: block; margin-bottom: 15px; }
    .f-buttons { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 10px; position: relative;}
    .btn { padding: 8px 12px; border-radius: 8px; font-...   }
    
    // Yazdırma İşlevleri (Önceki modüllerle aynı)
    function showPrintOptions() { document.getElementById('printOptionsBox').style.display = document.getElementById('printOptionsBox').style.display === 'flex' ? 'none' : 'flex'; }
    function setPrintFormat(format) {
        document.body.classList.remove('print-a4', 'print-a5', 'print-continuous', 'print-pdf');
        document.body.classList.add(`print-${format === 'pdf' ? 'a4' : format}`);
        document.getElementById('printOptionsBox').style.display = 'none';
        window.print(); 
    }

    function kaydet() { alert("Alış İrsaliyesi Kaydedildi. (Stok/Cari Etkilenmedi)"); }
    function faturayaDonustur() {
         alert("İrsaliye faturaya dönüştürülüyor. STOK GİRİŞİ ve CARİ BORÇ HAREKETİ GERÇEKLEŞTİ.");
         window.location.href = '/fatura_alis_kes'; 
    }

    window.onload = function() {
        addRow('STK100', 'PARCA-001', 'Amortisör Ön Seti', 5, 'ADET', 850.00);
        addRow('STK200', 'PARCA-002', 'Yağ Filtresi', 50, 'ADET', 50.00);
        fillEmptyRows();
    ...
*** SON: 4-irsaliye_alis.txt ***

*** BAŞLANGIÇ: 4-irsaliye_satis.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Satış İrsaliyesi (Çoklu Çıktı)</title>
  <style>
    /* 1. GENEL TASARIM VE A4 DÜZENİ */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    body { background: #f0f7ff; padding: 16px; transition: all 0.2s; } /* Format değişimini görmek için geçiş eklendi */
    .container {
      width: 20.5cm; /* Varsayılan A4 genişliği */
      min-height: 29.7cm; /* Varsayılan A4 yüksekliği */
      background: white;
      margin: 0 auto;
      padding: 20px 30px; 
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      transition: all 0.2s;
    }
    
    /* TUŞLAR (Yazdırmada Gizlenecek) */
    .no-print { display: block; margin-bottom: 15px; }
    .f-buttons { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 10px; position: relative;}
...    document.body.classList.add(`print-${format}`);

        if (format === 'pdf') {
            // PDF için A4 düzenini kullan
            document.body.classList.remove('print-pdf');
            document.body.classList.add('print-a4');
        }

        // Seçim kutusunu gizle
        document.getElementById('printOptionsBox').style.display = 'none';
        
        // Yazdırma iletişim kutusunu aç
        // Tarayıcı, fiziksel kağıt boyutunu (@page CSS kuralı) ve "PDF Olarak Kaydet" seçeneğini buradan kontrol eder.
        window.print(); 
    }


    function kaydet() { alert("Satış İrsaliyesi Kaydedildi."); }
    function faturayaDonustur() {
         alert("İrsaliye faturaya dönüştürülüyor.");
         window.location.href = '/fatura_kes'; 
    }

    window.onload = function() {
        addRow('SLY12435', 'FB-2025-A', 'Fren Balatası Seti', 10, 'ADET', 1200.00);
        addRow('ROT789', 'RB-2025-B', 'Rot Başlığı', 20, 'ADET', 250.00);
        fillEmptyRows(); // Yüklenirken A4'e göre boşlukları doldur
    }
    
    document.addEventListener("keydown...
*** SON: 4-irsaliye_satis.txt ***

*** BAŞLANGIÇ: 5-ambar_islem_giris.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Ambar İşlem Giriş Ekranı</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      height: 95vh;
    }
    
    /* TUŞLAR */
    .top-buttons { display: flex; gap: 8px; margin-bottom: 15px; flex-wrap: wrap; }
    .btn { padding: 8px 12px; border-radius: 6px; font-weight: 600; font-size: 13px; cursor: pointer; border: none; position: relative; transition: background 0.2s; }
    .btn-f2 { background: #2563eb; color: white; }...'
            sayimSummary.style.display = 'block';
            
            // Tabloyu Sayım'a göre ayarla
            transferHeaders.forEach(th => th.style.display = 'none');
            sayimHeaders.forEach(th => th.style.display = 'table-cell');
             // Transfer/Sayım data hücrelerini Sayım moduna göre ayarla
            transferData.forEach(td => td.style.display = 'none');
            sayimData.forEach(td => td.style.display = 'table-cell');
            
             // Örnek satırları ayarla
            transferRow.style.display = 'none';
            sayimRow.style.display = 'table-row';
        }
    }

    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Yeni İşlem (Transfer/Sayım) kaydı başlatılıyor."); }
      if (event.key === "F4") { event.preventDefault(); alert("F4: Stok Kartı Arama Ekranı açılıyor."); }
      if (event.key === "F5") { event.preventDefault(); alert("F5: İşlem kaydediliyor ve stok miktarları güncelleniyor (Kaydet)."); }
      if (event.key === "F10") { event.preventDefault(); alert("F10: Ekran kapatılıyor."); }
    });
    
    document.getElementById('operation-type').addEventListener('change', function() {
        updateScreenForOperation(this.value...
*** SON: 5-ambar_islem_giris.txt ***

*** BAŞLANGIÇ: 5-aylik_alis_satis_raporu.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Aylık Alış / Satış Raporu</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* ÜST BÖLÜM VE FİLTRELER */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr; /* 3 filtre grubu */
        gap: 12px;
        flex-grow: 1;
        margin-right: 20px;
        padding: 10px;
        border: 1px solid #e2e8...arar">-40.000,00</td>
            <td class="zarar">% -7,27</td>
            <td>99.000,00</td>
        </tr>
         <tr class="total-row">
            <td colspan="2">YILLIK GENEL TOPLAM</td>
            <td>9.550.000,00</td>
            <td>14.150.000,00</td>
            <td class="kar-zarar">4.600.000,00</td>
            <td>-</td>
            <td>2.547.000,00</td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div><strong>ORTALAMA AYLIK KÂR MARJI:</strong> % 32.50</div>
        <div><strong>EN YÜKSEK SATIŞ AYI:</strong> Mart (850.000,00 TL)</div>
        <div><strong>EN DÜŞÜK KÂR AYI:</strong> Nisan (-40.000,00 TL)</div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Safire Stok Programı v2.2 – Aylık Alış / Satış Raporu 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Rapor, seçilen yıl ve filtre...
*** SON: 5-aylik_alis_satis_raporu.txt ***

*** BAŞLANGIÇ: 5-cari_ekstresi_raporu.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Cari Ekstresi Raporu</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 20.5cm;
      min-height: 29.7cm;
      background: white;
      margin: 0 auto;
      padding: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }

    /* YAZDIRMA STİLLERİ */
    .no-print { display: block !important; }
    @media print {
      .no-print, .no-print * { display: none !important; }
      .container { margin: 0; padding: 0; width: 100%; box-shadow: none; border-radius: 0; }
      /* Raporda kullanılan renkli bakiyeleri siyah beyaz yazıcılar için iyileştirir */
      .bakiye-borc { color: black !important; font-weight: bold; }
      .bakiye-alacak { color: black !important; font...nt = borc.toFixed(2).replace('.', ',') + ' TL';
        document.getElementById('toplamAlacak').textContent = alacak.toFixed(2).replace('.', ',') + ' TL';

        const finalBakiyeDeger = document.getElementById('finalBakiyeDeger');
        
        let bakiyeMetni = finalBakiye.toFixed(2).replace('.', ',') + ' TL';
        let bakiyeClass = 'bakiye-sifir';

        if (finalBakiye > 0) {
            bakiyeMetni += ' (BORÇ)';
            bakiyeClass = 'bakiye-borc';
        } else if (finalBakiye < 0) {
            bakiyeMetni = Math.abs(finalBakiye).toFixed(2).replace('.', ',') + ' TL (ALACAK)';
            bakiyeClass = 'bakiye-alacak';
        } else {
             bakiyeMetni += ' (KAPALI)';
        }

        finalBakiyeDeger.textContent = bakiyeMetni;
        finalBakiyeDeger.className = bakiyeClass;
    }


    window.onload = function() {
        renderRaporHareketleri(CARI_HAREKETLERI);
    }
    
    // F TUŞU KISAYOLLARI 
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event....
*** SON: 5-cari_ekstresi_raporu.txt ***

*** BAŞLANGIÇ: 5-fatura_listesi_raporu.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Fatura Listesi Raporu</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* ÜST BÖLÜM VE FİLTRELER */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters {
        display: grid;
        grid-template-columns: 1.5fr 1fr 1fr 1.5fr 1.5fr; /* 5 filtre grubu */
        gap: 12px;
        flex-grow: 1;
        margin-right: 20px;
        padding: 10px;
        border:...<td>FS-00080</td>
            <td class="satış">Satış</td>
            <td>CR-0021</td>
            <td>Akdeniz Servis Hizmetleri</td>
            <td>01.10.2025</td>
            <td>5.200,00 TL</td>
            <td>1.040,00 TL</td>
            <td class="satış">6.240,00 TL</td>
            <td class="acik-fatura">V. Geçti</td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div><strong>RAPORLANAN FATURA ADEDİ:</strong> 1.540 Adet</div>
        <div><strong>TOPLAM SATIŞ (GENEL TOPLAM):</strong> 8.540.350,00 TL</div>
        <div><strong>TOPLAM ALIŞ (GENEL TOPLAM):</strong> 5.120.900,00 TL</div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Safire Stok Programı v2.2 – Fatura Listesi Raporu 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Rapor, seçilen filtre ve tarih aralığına göre güncelleniyor."); }
      if (event.key === "F3") { 
          event.preventDefault(); 
          ...
*** SON: 5-fatura_listesi_raporu.txt ***

*** BAŞLANGIÇ: 5-maliyet_raporu.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Maliyet ve Kârlılık Raporu</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* ÜST BÖLÜM VE FİLTRELER */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr 1fr; /* 5 filtre grubu */
        gap: 12px;
        flex-grow: 1;
        margin-right: 20px;
        padding: 10px;
        border: 1px...td>YEDEK</td>
            <td>RZ-001</td>
            <td>Radyatör Hortum Seti</td>
            <td>51 Set</td>
            <td>180,00 TL</td>
            <td>450,00 TL</td>
            <td class="pozitif-kar">270,00 TL</td>
            <td class="pozitif-kar">% 150,00</td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div><strong>RAPORLANAN ÜRÜN ÇEŞİDİ:</strong> 345</div>
        <div><strong>TOPLAM STOK MALİYET DEĞERİ:</strong> <span class="maliyet-tl">1.550.800,00 TL</span></div>
        <div><strong>TOPLAM POTANSİYEL KÂR (BRÜT):</strong> <span class="pozitif-kar">850.450,00 TL</span></div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Safire Stok Programı v2.2 – Maliyet ve Kârlılık Raporu 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Rapor, seçilen filtre ve maliyet yöntemine göre güncelleniyor."); }
      if (event.key === "F3") { 
          event.preventDefault(); 
          alert("...
*** SON: 5-maliyet_raporu.txt ***

*** BAŞLANGIÇ: 5-minimum_stok_raporu_duzeltilmis.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Minimum Stok Raporu (Düzeltilmiş)</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* ÜST BÖLÜM VE FİLTRELER */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 12px; flex-grow: 1; margin-right: 20px; padding: 10px; border: 1px solid #e2e8f0; border-radius: 8px; }
    .filter-group label { display: block; font-...eksi-fark">-6</td>
        </tr>
        <tr class="warning-row">
            <td>YAG-GEN</td>
            <td>YAG-5W40-01</td>
            <td>Sentetik Motor Yağı 5/40</td>
            <td>Litre</td>
            <td>100</td>
            <td>85</td>
            <td class="eksi-fark">-15</td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div><strong>TOPLAM STOK ÇEŞİDİ:</strong> 350</div>
        <div><strong>MİN. ALTINDAKİ ÜRÜN ÇEŞİDİ:</strong> 15</div>
        <div><strong>TOPLAM EKSİK MİKTAR:</strong> 155 Adet/Litre</div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Safire Stok Programı v2.2 – Minimum Stok Raporu 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Rapor, güncel stok durumuna göre yenileniyor."); }
      if (event.key === "F3") { 
          event.preventDefault(); 
          // Yüksek hacimli yazdırma için A4, A5, Sürekli Form seçenekleri varsayılır.
          alert("F3: Rapor Yazdırma Önizlemesine gönderiliyor. Buradan çıktı format...
*** SON: 5-minimum_stok_raporu_duzeltilmis.txt ***

*** BAŞLANGIÇ: 5-stok_abc_raporu.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Stok ABC / Pareto Analizi Raporu</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* ÜST BÖLÜM VE FİLTRELER */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr; /* 4 filtre grubu */
        gap: 12px;
        flex-grow: 1;
        margin-right: 20px;
        padding: 10px;
        border: 1px solid #e2...   <tr class="group-C">
            <td>C</td>
            <td>O-ESK</td>
            <td>Y-0001</td>
            <td>Eski Model Yağ Filtresi</td>
            <td>1,50</td>
            <td>0,00001</td>
            <td>100,00</td>
            <td><div class="cumulative-bar-container"><div class="cumulative-bar" style="width: 100%;></div></div></td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div><strong>A GRUBU ÜRÜN ÇEŞİDİ:</strong> 400 (% 2)</div>
        <div><strong>B GRUBU ÜRÜN ÇEŞİDİ:</strong> 1.600 (% 8)</div>
        <div><strong>C GRUBU ÜRÜN ÇEŞİDİ:</strong> 18.000 (% 90)</div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Safire Stok Programı v2.2 – ABC / Pareto Analiz Raporu 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Analiz, seçilen kritere göre yeniden hesaplanıyor."); }
      if (event.key === "F3") { 
          event.preventDefault(); 
          alert("F3: Rapor Yazdırma Ön...
*** SON: 5-stok_abc_raporu.txt ***

*** BAŞLANGIÇ: 5-stok_envanter_raporu_duzeltilmis.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Genel Stok Envanter Raporu (Düzeltilmiş)</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* TUŞLAR VE FİLTRELER (Önceki raporla aynı) */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters { display: grid; grid-template-columns: 1fr 1fr 1fr 1fr 1fr; gap: 12px; flex-grow: 1; margin-right: 20px; padding: 10px; border: 1px solid #e2e8f0; border-radius: 8px; }
...L</td>
        </tr>
        <tr>
            <td>YAG-GEN</td>
            <td>YAĞ-SYN-5W30</td>
            <td>Tam Sentetik Motor Yağı</td>
            <td>Litre</td>
            <td>A-01</td>
            <td>450</td>
            <td>120,00 TL</td>
            <td>190,00 TL</td>
            <td>54.000,00 TL</td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div class="total-value"><strong>TOPLAM STOK ÇEŞİT SAYISI:</strong> 345</div>
        <div class="total-value"><strong>TOPLAM STOK MİKTARI:</strong> 12.550 Adet/Litre</div>
        <div class="total-value"><strong>GENEL STOK DEĞERİ (ALIŞ):</strong> 1.550.800,00 TL</div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Genel Stok Envanter Raporu 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Rapor, seçilen filtre ve tarihe göre güncelleniyor."); }
      if (event.key === "F3") { 
          event.preventDefault(); 
          alert("F3: Rapor Yazdırma Önizlemesine gönder...
*** SON: 5-stok_envanter_raporu_duzeltilmis.txt ***

*** BAŞLANGIÇ: 5-stok_hareket_raporu_duzeltilmis.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Stok Ürün Hareket Ekstresi (Düzeltilmiş)</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* TUŞLAR VE FİLTRELER (Önceki raporla aynı) */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters { display: grid; grid-template-columns: 2fr 1fr 1fr 1fr; gap: 12px; flex-grow: 1; margin-right: 20px; padding: 10px; border: 1px solid #e2e8f0; border-radius: 8px; }
    .filter...Güven Oto)</td>
            <td class="giris">50</td>
            <td class="cikis">0</td>
            <td class="giris">185</td>
        </tr>
        <tr>
            <td>OTO-PAR</td>
            <td>FB-2025-A</td>
            <td>20.04.2025</td>
            <td>İrsaliye</td>
            <td>IS-2025-0045</td>
            <td>Mağaza Sevkiyatı</td>
            <td>CR-0012 (Akdeniz)</td>
            <td class="giris">0</td>
            <td class="cikis">67</td>
            <td class="bakiye-final">118</td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div class="total-giris"><strong>Toplam Giriş:</strong> 200 Adet</div>
        <div class="total-cikis"><strong>Toplam Çıkış:</strong> 82 Adet</div>
        <div class="net-bakiye"><strong>NET STOK BAKİYESİ:</strong> 118 Adet</div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Stok Ürün Hareket Ekstresi 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Rapor yeniden oluşturuluyor...
*** SON: 5-stok_hareket_raporu_duzeltilmis.txt ***

*** BAŞLANGIÇ: 5-stok_sayim_raporu.html ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Stok Sayım Raporu</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* ÜST BÖLÜM VE FİLTRELER */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr; /* 4 filtre grubu */
        gap: 12px;
        flex-grow: 1;
        margin-right: 20px;
        padding: 10px;
        border: 1px solid #e2e8f...       <td>0,00 TL</td>
        </tr>
        <tr class="fark-row-eksi">
            <td>OTO-PAR</td>
            <td>RZ-001</td>
            <td>Radyatör Hortum Seti</td>
            <td>Set</td>
            <td>55</td>
            <td>51</td>
            <td class="eksi-fark">-4</td>
            <td class="eksi-fark">-280,00 TL</td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div><strong>FARKLI ÜRÜN ÇEŞİDİ:</strong> 87</div>
        <div><strong>TOPLAM MİKTAR FARKI:</strong> -245 Adet (Net)</div>
        <div><strong>NET DEĞER FARKI:</strong> <span class="eksi-fark">-1.850,00 TL</span> (Maliyet)</div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Safire Stok Programı v2.2 – Stok Sayım Fark Raporu 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Rapor, güncel sayım ve sisteme göre yenileniyor."); }
      if (event.key === "F3") { 
          event.preventDefault(); 
          alert("F3: Rapor Yazdırma Önizlemesine gönderiliyor. Yüksek yoğunluk...
*** SON: 5-stok_sayim_raporu.html ***

*** BAŞLANGIÇ: 5-stok_sayim_raporu.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Stok Sayım Raporu</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* ÜST BÖLÜM VE FİLTRELER */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr; /* 4 filtre grubu */
        gap: 12px;
        flex-grow: 1;
        margin-right: 20px;
        padding: 10px;
        border: 1px solid #e2e8f...       <td>0,00 TL</td>
        </tr>
        <tr class="fark-row-eksi">
            <td>OTO-PAR</td>
            <td>RZ-001</td>
            <td>Radyatör Hortum Seti</td>
            <td>Set</td>
            <td>55</td>
            <td>51</td>
            <td class="eksi-fark">-4</td>
            <td class="eksi-fark">-280,00 TL</td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div><strong>FARKLI ÜRÜN ÇEŞİDİ:</strong> 87</div>
        <div><strong>TOPLAM MİKTAR FARKI:</strong> -245 Adet (Net)</div>
        <div><strong>NET DEĞER FARKI:</strong> <span class="eksi-fark">-1.850,00 TL</span> (Maliyet)</div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Safire Stok Programı v2.2 – Stok Sayım Fark Raporu 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Rapor, güncel sayım ve sisteme göre yenileniyor."); }
      if (event.key === "F3") { 
          event.preventDefault(); 
          alert("F3: Rapor Yazdırma Önizlemesine gönderiliyor. Yüksek yoğunluk...
*** SON: 5-stok_sayim_raporu.txt ***

*** BAŞLANGIÇ: 6-kasa_banka_giris.html ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Kasa / Banka İşlem Giriş Ekranı</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      height: 95vh;
    }
    
    /* TUŞLAR */
    .top-buttons { display: flex; gap: 8px; margin-bottom: 20px; flex-wrap: wrap; }
    .btn { padding: 8px 12px; border-radius: 6px; font-weight: 600; font-size: 13px; cursor: pointer; border: none; position: relative; transition: background 0.2s; }
    .btn-f2 { background: #2563eb; color:...EM GİRİŞ EKRANI - ÖDEME (ÇIKIŞ)';
            cariBakiye.textContent = 'Cari Bakiyesi: -41.500,00 TL (Borçlu)';
            cariArea.style.display = 'block';
            virmanArea.style.display = 'none';
        } else if (type === 'virman') {
            // Virman (Mavi)
            amountArea.classList.add('virman-color');
            titleElement.style.color = '#2563eb';
            titleElement.textContent = 'KASA / BANKA İŞLEM GİRİŞ EKRANI - VİRMAN (TRANSFER)';
            cariBakiye.textContent = 'İşlem Tipi: Kasa/Banka arası transfer.';
            cariArea.style.display = 'none';
            virmanArea.style.display = 'block';
        }
    }

    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Yeni Kasa/Banka fişi başlatılıyor."); }
      if (event.key === "F4") { event.preventDefault(); alert("F4: Cari Kartı Arama Ekranı açılıyor."); }
      if (event.key === "F5") { event.preventDefault(); alert("F5: İşlem kaydediliyor ve Kasa/Banka/Cari bakiyeleri güncelleniyor (Kaydet)."); }
      if (event.key === "F10") { event.preventDefault(); alert("F10:...
*** SON: 6-kasa_banka_giris.html ***

*** BAŞLANGIÇ: 6-kasa_banka_giris.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Kasa / Banka İşlem Giriş Ekranı</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      height: 95vh;
    }
    
    /* TUŞLAR */
    .top-buttons { display: flex; gap: 8px; margin-bottom: 20px; flex-wrap: wrap; }
    .btn { padding: 8px 12px; border-radius: 6px; font-weight: 600; font-size: 13px; cursor: pointer; border: none; position: relative; transition: background 0.2s; }
    .btn-f2 { background: #2563eb; color:...EM GİRİŞ EKRANI - ÖDEME (ÇIKIŞ)';
            cariBakiye.textContent = 'Cari Bakiyesi: -41.500,00 TL (Borçlu)';
            cariArea.style.display = 'block';
            virmanArea.style.display = 'none';
        } else if (type === 'virman') {
            // Virman (Mavi)
            amountArea.classList.add('virman-color');
            titleElement.style.color = '#2563eb';
            titleElement.textContent = 'KASA / BANKA İŞLEM GİRİŞ EKRANI - VİRMAN (TRANSFER)';
            cariBakiye.textContent = 'İşlem Tipi: Kasa/Banka arası transfer.';
            cariArea.style.display = 'none';
            virmanArea.style.display = 'block';
        }
    }

    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Yeni Kasa/Banka fişi başlatılıyor."); }
      if (event.key === "F4") { event.preventDefault(); alert("F4: Cari Kartı Arama Ekranı açılıyor."); }
      if (event.key === "F5") { event.preventDefault(); alert("F5: İşlem kaydediliyor ve Kasa/Banka/Cari bakiyeleri güncelleniyor (Kaydet)."); }
      if (event.key === "F10") { event.preventDefault(); alert("F10:...
*** SON: 6-kasa_banka_giris.txt ***

*** BAŞLANGIÇ: 7-cek_senet_giris.html ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Çek / Senet Takip Ekranı</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      height: 95vh;
    }
    
    /* TUŞLAR */
    .top-buttons { display: flex; gap: 8px; margin-bottom: 20px; flex-wrap: wrap; }
    .btn { padding: 8px 12px; border-radius: 6px; font-weight: 600; font-size: 13px; cursor: pointer; border: none; position: relative; transition: background 0.2s; }
    .btn-f2 { background: #2563eb; color: white;...leElement.textContent = `ÇEK / SENET TAKİP EKRANI - ${titleText}`;
        statusElement.textContent = statusText;
        statusElement.style.backgroundColor = isAlinan ? '#ecfdf5' : '#fffbeb';
        statusElement.style.color = statusColor;
        
        // Alınan çeklerde borçlu cari, Verilen çeklerde alacaklı cari (bizim muhatabımız)
        const cariLabel = document.querySelector('.main-info .form-group-full label');
        cariLabel.textContent = isAlinan ? 'Borçlu Cari Kodu (F4)' : 'Alacaklı Cari Kodu (F4)';
    }

    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Yeni Çek/Senet kaydı başlatılıyor."); }
      if (event.key === "F4") { event.preventDefault(); alert("F4: Cari Kartı Arama Ekranı açılıyor."); }
      if (event.key === "F5") { event.preventDefault(); alert("F5: Çek/Senet kaydı veritabanına işleniyor (Kaydet)."); }
      if (event.key === "F6") { event.preventDefault(); alert("F6: Çek/Senet Durum Değişikliği (Bankaya Tahsil, Ciro, Ödeme vb.) ekranı açılıyor."); }
      if (event.key === "F10") { event.preventDefault(); alert("F10: Ekran kapatılıyor."); }
    ...
*** SON: 7-cek_senet_giris.html ***

*** BAŞLANGIÇ: 7-cek_senet_giris.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Çek / Senet Takip Ekranı</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      height: 95vh;
    }
    
    /* TUŞLAR */
    .top-buttons { display: flex; gap: 8px; margin-bottom: 20px; flex-wrap: wrap; }
    .btn { padding: 8px 12px; border-radius: 6px; font-weight: 600; font-size: 13px; cursor: pointer; border: none; position: relative; transition: background 0.2s; }
    .btn-f2 { background: #2563eb; color: white;...leElement.textContent = `ÇEK / SENET TAKİP EKRANI - ${titleText}`;
        statusElement.textContent = statusText;
        statusElement.style.backgroundColor = isAlinan ? '#ecfdf5' : '#fffbeb';
        statusElement.style.color = statusColor;
        
        // Alınan çeklerde borçlu cari, Verilen çeklerde alacaklı cari (bizim muhatabımız)
        const cariLabel = document.querySelector('.main-info .form-group-full label');
        cariLabel.textContent = isAlinan ? 'Borçlu Cari Kodu (F4)' : 'Alacaklı Cari Kodu (F4)';
    }

    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Yeni Çek/Senet kaydı başlatılıyor."); }
      if (event.key === "F4") { event.preventDefault(); alert("F4: Cari Kartı Arama Ekranı açılıyor."); }
      if (event.key === "F5") { event.preventDefault(); alert("F5: Çek/Senet kaydı veritabanına işleniyor (Kaydet)."); }
      if (event.key === "F6") { event.preventDefault(); alert("F6: Çek/Senet Durum Değişikliği (Bankaya Tahsil, Ciro, Ödeme vb.) ekranı açılıyor."); }
      if (event.key === "F10") { event.preventDefault(); alert("F10: Ekran kapatılıyor."); }
    ...
*** SON: 7-cek_senet_giris.txt ***

*** BAŞLANGIÇ: 8-stok_envanter_raporu_duzeltilmis.html ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Genel Stok Envanter Raporu (Düzeltilmiş)</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    
    /* TUŞLAR VE FİLTRELER (Önceki raporla aynı) */
    .top-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; flex-wrap: wrap; }
    .filters { display: grid; grid-template-columns: 1fr 1fr 1fr 1fr 1fr; gap: 12px; flex-grow: 1; margin-right: 20px; padding: 10px; border: 1px solid #e2e8f0; border-radius: 8px; }
...L</td>
        </tr>
        <tr>
            <td>YAG-GEN</td>
            <td>YAĞ-SYN-5W30</td>
            <td>Tam Sentetik Motor Yağı</td>
            <td>Litre</td>
            <td>A-01</td>
            <td>450</td>
            <td>120,00 TL</td>
            <td>190,00 TL</td>
            <td>54.000,00 TL</td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
        <div class="total-value"><strong>TOPLAM STOK ÇEŞİT SAYISI:</strong> 345</div>
        <div class="total-value"><strong>TOPLAM STOK MİKTARI:</strong> 12.550 Adet/Litre</div>
        <div class="total-value"><strong>GENEL STOK DEĞERİ (ALIŞ):</strong> 1.550.800,00 TL</div>
    </div>

    <div class="footer">
      Safire Bilgisayar • Genel Stok Envanter Raporu 💙
    </div>

  </div>

  <script>
    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Rapor, seçilen filtre ve tarihe göre güncelleniyor."); }
      if (event.key === "F3") { 
          event.preventDefault(); 
          alert("F3: Rapor Yazdırma Önizlemesine gönder...
*** SON: 8-stok_envanter_raporu_duzeltilmis.html ***

*** BAŞLANGIÇ: 9-devir_islemleri.html ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Devir İşlemleri</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Arial', sans-serif; }
    body {
      background: #f0f4ff;
      padding: 20px;
    }
    .container {
      width: 21cm;
      min-height: 29.7cm;
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .header {
      text-align: center;
      margin-bottom: 24px;
    }
    .header h1 {
      font-size: 24px;
      font-weight: 800;
      color: #4338ca;
    }
    .filter {
      text-align: center;
      margin-bottom: 20px;
      font-size: 14px;
      color: #6b7280;
    }
    .info-box {
      background: #fefce8;
      padding: 16px;
      border-radius: 12px;
      border...table">
      <thead>
        <tr>
          <th style="width:20%;">Cari Kodu</th>
          <th style="width:35%;">Unvan</th>
          <th style="width:15%;">Borç (TL)</th>
          <th style="width:15%;">Alacak (TL)</th>
          <th style="width:15%;">Net Bakiye (TL)</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>CR-2025-0015</td>
          <td>Anadolu Otomotiv</td>
          <td>–</td>
          <td>45.000,00</td>
          <td><span style="color:green;">45.000,00 (Alacak)</span></td>
        </tr>
        <tr>
          <td>CR-2025-0018</td>
          <td>Oto Parça İthalat A.Ş.</td>
          <td>68.000,00</td>
          <td>–</td>
          <td><span style="color:red;">68.000,00 (Borç)</span></td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
      <div><strong>Toplam Kalan Adet:</strong> 131 adet</div>
      <div><strong>Toplam Stok Maliyeti:</strong> 332.400,00 TL</div>
      <div><strong>Ort. Birim Maliyet:</strong> 2.537,40 TL</div>
      <div><strong>Net Cari...
*** SON: 9-devir_islemleri.html ***

*** BAŞLANGIÇ: 9-devir_islemleri.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Devir İşlemleri</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Arial', sans-serif; }
    body {
      background: #f0f4ff;
      padding: 20px;
    }
    .container {
      width: 21cm;
      min-height: 29.7cm;
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .header {
      text-align: center;
      margin-bottom: 24px;
    }
    .header h1 {
      font-size: 24px;
      font-weight: 800;
      color: #4338ca;
    }
    .filter {
      text-align: center;
      margin-bottom: 20px;
      font-size: 14px;
      color: #6b7280;
    }
    .info-box {
      background: #fefce8;
      padding: 16px;
      border-radius: 12px;
      border...table">
      <thead>
        <tr>
          <th style="width:20%;">Cari Kodu</th>
          <th style="width:35%;">Unvan</th>
          <th style="width:15%;">Borç (TL)</th>
          <th style="width:15%;">Alacak (TL)</th>
          <th style="width:15%;">Net Bakiye (TL)</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>CR-2025-0015</td>
          <td>Anadolu Otomotiv</td>
          <td>–</td>
          <td>45.000,00</td>
          <td><span style="color:green;">45.000,00 (Alacak)</span></td>
        </tr>
        <tr>
          <td>CR-2025-0018</td>
          <td>Oto Parça İthalat A.Ş.</td>
          <td>68.000,00</td>
          <td>–</td>
          <td><span style="color:red;">68.000,00 (Borç)</span></td>
        </tr>
      </tbody>
    </table>

    <div class="summary">
      <div><strong>Toplam Kalan Adet:</strong> 131 adet</div>
      <div><strong>Toplam Stok Maliyeti:</strong> 332.400,00 TL</div>
      <div><strong>Ort. Birim Maliyet:</strong> 2.537,40 TL</div>
      <div><strong>Net Cari...
*** SON: 9-devir_islemleri.txt ***

*** BAŞLANGIÇ: 10-kullanıcı_ayarları.html ***
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Kullanıcı Ayarları</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body {
      background: #e0f2fe;
      padding: 20px;
    }
    .container {
      width: 21cm;
      min-height: 29.7cm;
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 25px rgba(15,23,42,0.15);
      border-radius: 10px;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 24px;
    }
    .title {
      font-size: 22px;
      font-weight: 800;
      color: #0f172a;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .title::before {
      content: "⚙️";
      font-size: 24px;
    }...        <label><input type="checkbox"> Web Grup</label>
          <label><input type="checkbox"> Açıklama</label>
          <label><input type="checkbox" checked> Son İşlem Tarihi</label>
        </div>

        <hr style="margin:12px 0; border-color:#e5e7eb;">

        <div class="row">
          <label>Son Yedek Tarihi:</label>
          <input type="text" value="10.11.2025 21:30" readonly>
        </div>
        <div class="row">
          <label>Yedek Yolu:</label>
          <input type="text" value="D:\Safire_Yedek\" readonly>
        </div>
        <div class="row">
          <button class="btn btn-f11" data-key="F11" data-aciklama="Yedek al">F11: Yedek Al</button>
          <button class="btn btn-f12" data-key="F12" data-aciklama="Yedeği geri yükle">F12: Geri Yükle</button>
        </div>
      </div>

    </div>

    <div class="footer">
      Safire Bilgisayar • Kullanıcı Ayarları • F11: Yedekle • F12: Geri Yükle
    </div>

  </div>

  <script>
    // Klavyeden...
*** SON: 10-kullanıcı_ayarları.html ***

*** BAŞLANGIÇ: 10-kullanıcı_ayarları.txt ***
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - Kullanıcı Ayarları</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body {
      background: #e0f2fe;
      padding: 20px;
    }
    .container {
      width: 21cm;
      min-height: 29.7cm;
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 25px rgba(15,23,42,0.15);
      border-radius: 10px;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 24px;
    }
    .title {
      font-size: 22px;
      font-weight: 800;
      color: #0f172a;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .title::before {
      content: "⚙️";
      font-size: 24px;
    }...        <label><input type="checkbox"> Web Grup</label>
          <label><input type="checkbox"> Açıklama</label>
          <label><input type="checkbox" checked> Son İşlem Tarihi</label>
        </div>

        <hr style="margin:12px 0; border-color:#e5e7eb;">

        <div class="row">
          <label>Son Yedek Tarihi:</label>
          <input type="text" value="10.11.2025 21:30" readonly>
        </div>
        <div class="row">
          <label>Yedek Yolu:</label>
          <input type="text" value="D:\Safire_Yedek\" readonly>
        </div>
        <div class="row">
          <button class="btn btn-f11" data-key="F11" data-aciklama="Yedek al">F11: Yedek Al</button>
          <button class="btn btn-f12" data-key="F12" data-aciklama="Yedeği geri yükle">F12: Geri Yükle</button>
        </div>
      </div>

    </div>

    <div class="footer">
      Safire Bilgisayar • Kullanıcı Ayarları • F11: Yedekle • F12: Geri Yükle
    </div>

  </div>

  <script>
    // Klavyeden...
*** SON: 10-kullanıcı_ayarları.txt ***

*** BAŞLANGIÇ: 11-e_belge_yonetimi.html ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - E-Belge Yönetim Ekranı</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      height: 95vh;
    }
    
    /* TUŞLAR */
    .top-buttons { display: flex; gap: 8px; margin-bottom: 15px; flex-wrap: wrap; }
    .btn { padding: 8px 12px; border-radius: 6px; font-weight: 600; font-size: 13px; cursor: pointer; border: none; position: relative; transition: background 0.2s; }
    .btn-f2 { background: #16a34a; color: white;...nt.textContent = 'E-ARŞİV FATURA TAKİP EKRANI (Giden)';
        } else if (type === 'e-irsaliye') {
            titleElement.textContent = 'E-İRSALİYE GÖNDERİM VE TAKİP EKRANI (Giden)';
        } else if (type === 'gelen') {
            titleElement.textContent = 'GELEN E-BELGE (Fatura/İrsaliye) TAKİP EKRANI';
        }
    }

    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Taslak fişlerden (Fatura/İrsaliye) E-Belge oluşturma işlemi başlatılıyor."); }
      if (event.key === "F3") { event.preventDefault(); alert("F3: Seçili E-Belge GİB sistemine gönderiliyor."); }
      if (event.key === "F4") { event.preventDefault(); alert("F4: Cari Kartı Arama Ekranı açılıyor."); }
      if (event.key === "F5") { event.preventDefault(); alert("F5: GİB sistemi ile bağlantı kurulup seçilen/tüm belgelerin son durumu sorgulanıyor ve güncelleniyor."); }
      if (event.key === "F6") { event.preventDefault(); alert("F6: Seçilen belgenin HTML/PDF önizlemesi açılıyor ve indirme seçenekleri sunuluyor."); }
      if (event.key === "F10") { event.preventDefault(); alert...
*** SON: 11-e_belge_yonetimi.html ***

*** BAŞLANGIÇ: 11-e_belge_yonetimi.txt ***
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Safire Stok Programı - E-Belge Yönetim Ekranı</title>
  <style>
    /* ORTAK STİLLER */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #f0f7ff; padding: 16px; }
    .container {
      width: 21cm; 
      min-height: 29.7cm; 
      background: white;
      margin: 0 auto;
      padding: 24px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      height: 95vh;
    }
    
    /* TUŞLAR */
    .top-buttons { display: flex; gap: 8px; margin-bottom: 15px; flex-wrap: wrap; }
    .btn { padding: 8px 12px; border-radius: 6px; font-weight: 600; font-size: 13px; cursor: pointer; border: none; position: relative; transition: background 0.2s; }
    .btn-f2 { background: #16a34a; color: white;...nt.textContent = 'E-ARŞİV FATURA TAKİP EKRANI (Giden)';
        } else if (type === 'e-irsaliye') {
            titleElement.textContent = 'E-İRSALİYE GÖNDERİM VE TAKİP EKRANI (Giden)';
        } else if (type === 'gelen') {
            titleElement.textContent = 'GELEN E-BELGE (Fatura/İrsaliye) TAKİP EKRANI';
        }
    }

    document.addEventListener("keydown", function(event) {
      if (event.key === "F2") { event.preventDefault(); alert("F2: Taslak fişlerden (Fatura/İrsaliye) E-Belge oluşturma işlemi başlatılıyor."); }
      if (event.key === "F3") { event.preventDefault(); alert("F3: Seçili E-Belge GİB sistemine gönderiliyor."); }
      if (event.key === "F4") { event.preventDefault(); alert("F4: Cari Kartı Arama Ekranı açılıyor."); }
      if (event.key === "F5") { event.preventDefault(); alert("F5: GİB sistemi ile bağlantı kurulup seçilen/tüm belgelerin son durumu sorgulanıyor ve güncelleniyor."); }
      if (event.key === "F6") { event.preventDefault(); alert("F6: Seçilen belgenin HTML/PDF önizlemesi açılıyor ve indirme seçenekleri sunuluyor."); }
      if (event.key === "F10") { event.preventDefault(); alert...
*** SON: 11-e_belge_yonetimi.txt ***
