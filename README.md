[pengiriman-truk.html.html](https://github.com/user-attachments/files/32950419/pengiriman-truk.html.html)<!DOCTYPE html>
<html lang="id"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>BIMA LOGISTICS - Manajemen Pengiriman Barang</title>
<link href="https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#eef1f4;--card:#fff;--ink:#12263a;--mut:#5d6f80;--line:#d9e0e7;--acc:#f2a900;--ok:#1f8a5b;--bad:#c4392f;--blue:#2b6cb0;--nav:#12263a;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0e1a26;--card:#162636;--ink:#e6edf3;--mut:#93a5b6;--line:#263a4e;--nav:#0a131c}}
:root[data-theme="dark"]{--bg:#0e1a26;--card:#162636;--ink:#e6edf3;--mut:#93a5b6;--line:#263a4e;--nav:#0a131c}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:500 16px/1.45 "Barlow Semi Condensed",system-ui,sans-serif}
.app{display:flex;min-height:100vh}
aside{width:210px;background:var(--nav);color:#cdd8e3;padding:20px 12px;position:sticky;top:0;height:100vh;flex:none}
.logo{font-weight:700;font-size:22px;line-height:1.1;letter-spacing:.04em;color:#fff;padding:0 10px 18px}.logo i{font-style:normal;color:var(--acc)}
#nav{display:flex;flex-direction:column;gap:2px}
#nav button{all:unset;cursor:pointer;padding:10px 12px;border-radius:8px;font-size:16px;border-left:3px solid transparent}
#nav button:hover{background:rgba(255,255,255,.07)}
#nav button.on{background:rgba(242,169,0,.14);color:#fff;border-left-color:var(--acc)}
#nav button:focus-visible,button:focus-visible,input:focus-visible,select:focus-visible{outline:2px solid var(--acc);outline-offset:2px}
main{flex:1;min-width:0;padding:24px 28px 40px;max-width:1200px}
h1{font-size:26px;margin:0 0 4px}h2{font-size:18px;margin:0 0 12px}
.sub{color:var(--mut);margin:0 0 20px}
.grid{display:grid;gap:14px}.k4{grid-template-columns:repeat(auto-fit,minmax(190px,1fr))}.c2{grid-template-columns:repeat(auto-fit,minmax(320px,1fr))}
.card{background:var(--card);border:1px solid var(--line);border-radius:10px;padding:16px;margin-bottom:14px}
.kpi b{display:block;font-size:28px;line-height:1.1}.kpi span{color:var(--mut);font-size:14px}
.kpi.a{border-left:4px solid var(--acc)}.kpi.g{border-left:4px solid var(--ok)}.kpi.b{border-left:4px solid var(--blue)}
form{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:12px;align-items:end}
label{display:flex;flex-direction:column;gap:4px;font-size:14px;color:var(--mut)}
input,select{font:inherit;padding:9px 10px;border:1px solid var(--line);border-radius:7px;background:var(--bg);color:var(--ink);width:100%}
.btn{font:inherit;font-weight:600;border:0;border-radius:7px;padding:10px 16px;background:var(--acc);color:#2b1f00;cursor:pointer}
.btn.s{padding:5px 10px;font-size:14px;background:var(--bg);color:var(--ink);border:1px solid var(--line)}.btn.d{color:var(--bad)}
.full{grid-column:1/-1}.est{background:var(--bg);border-radius:7px;padding:9px 12px;font-size:15px}
.tw{overflow-x:auto}table{width:100%;border-collapse:collapse;font-size:15px}
th{text-align:left;color:var(--mut);font-weight:600;padding:8px;border-bottom:2px solid var(--line);white-space:nowrap}
td{padding:9px 8px;border-bottom:1px solid var(--line);white-space:nowrap}
.bd{padding:2px 9px;border-radius:99px;font-size:13px;font-weight:600;background:var(--line)}
.bd.run{background:#fde9b0;color:#5c4200}.bd.ok{background:#cdeedd;color:#14573a}.bd.no{background:#f6d4d0;color:#7d211a}.bd.pl{background:#d6e6f7;color:#1c4a7a}
.bar{height:8px;background:var(--line);border-radius:9px;overflow:hidden;min-width:90px}.bar i{display:block;height:100%;background:var(--acc)}
svg.map{width:100%;height:auto;background:var(--bg);border-radius:8px}
textarea{width:100%;min-height:120px;font:13px/1.4 monospace;background:var(--bg);color:var(--ink);border:1px solid var(--line);border-radius:7px;padding:10px}
#toast{position:fixed;left:50%;transform:translateX(-50%);bottom:calc(76px + env(safe-area-inset-bottom,0px));background:var(--nav);color:#fff;padding:10px 18px;border-radius:8px;opacity:0;pointer-events:none;transition:opacity .2s;z-index:9}
#toast.on{opacity:1}
@media(max-width:800px){
.app{display:block}
aside{position:fixed;left:0;right:0;bottom:0;top:auto;width:auto;height:auto;padding:6px 6px calc(6px + env(safe-area-inset-bottom,0px));z-index:5}
.logo{display:none}#nav{flex-direction:row;overflow-x:auto}
#nav button{white-space:nowrap;padding:9px 12px;border-left:0;border-bottom:3px solid transparent}
#nav button.on{border-bottom-color:var(--acc)}
main{padding:16px 14px 90px}}
body.out aside{display:none}.login{max-width:380px;margin:6vh auto 0}.login .logo{color:var(--ink);padding:0 0 10px}
.who{display:flex;gap:8px;align-items:center;justify-content:flex-end;margin-bottom:10px;color:var(--mut);font-size:15px}
.ac{position:relative}.acl{position:absolute;z-index:6;left:0;right:0;top:100%;margin:2px 0 0;padding:4px;list-style:none;background:var(--card);border:1px solid var(--line);border-radius:8px;box-shadow:0 6px 18px rgba(0,0,0,.18);max-height:240px;overflow:auto}
.acl li{padding:7px 9px;border-radius:6px;cursor:pointer;color:var(--ink)}.acl li small{color:var(--mut)}.acl li:hover,.acl li.on{background:var(--bg)}.acl .none{color:var(--mut);cursor:default}
.ov{position:fixed;inset:0;background:rgba(10,19,28,.55);display:flex;align-items:flex-start;justify-content:center;padding:calc(4vh + env(safe-area-inset-top,0px)) 14px 24px;z-index:20;overflow:auto}
.dlg{background:var(--card);border:1px solid var(--line);border-radius:12px;padding:18px;width:100%;max-width:640px}
.dlg h2{margin-top:0}.dlg .full{display:flex;gap:8px;flex-wrap:wrap}
@media(prefers-reduced-motion:reduce){*{transition:none!important}}
</style></head>
<body><div class="app">
<aside><div class="logo">BIMA<br><i>LOGISTICS</i></div><nav id="nav"></nav></aside>
<main id="main"></main></div><div id="modal"></div><div id="toast" role="status"></div>
<script>
const $=s=>document.querySelector(s);
const esc=s=>String(s).replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const rp=n=>'Rp '+Math.round(n).toLocaleString('id-ID');
const G=`Jakarta|DKI Jakarta|-6.21|106.85
Bekasi|Jawa Barat|-6.24|106.99
Bogor|Jawa Barat|-6.60|106.80
Depok|Jawa Barat|-6.40|106.82
Bandung|Jawa Barat|-6.92|107.61
Cirebon|Jawa Barat|-6.71|108.56
Tasikmalaya|Jawa Barat|-7.33|108.22
Sukabumi|Jawa Barat|-6.92|106.93
Tangerang|Banten|-6.18|106.63
Serang|Banten|-6.12|106.15
Semarang|Jawa Tengah|-6.97|110.42
Surakarta|Jawa Tengah|-7.57|110.82
Purwokerto|Jawa Tengah|-7.43|109.24
Tegal|Jawa Tengah|-6.87|109.14
Pekalongan|Jawa Tengah|-6.89|109.68
Kudus|Jawa Tengah|-6.80|110.84
Magelang|Jawa Tengah|-7.47|110.22
Yogyakarta|DI Yogyakarta|-7.80|110.36
Surabaya|Jawa Timur|-7.25|112.75
Malang|Jawa Timur|-7.98|112.63
Kediri|Jawa Timur|-7.82|112.01
Madiun|Jawa Timur|-7.63|111.52
Probolinggo|Jawa Timur|-7.75|113.22
Jember|Jawa Timur|-8.17|113.70
Banyuwangi|Jawa Timur|-8.22|114.37
Denpasar|Bali|-8.65|115.22
Mataram|Nusa Tenggara Barat|-8.58|116.12
Kupang|Nusa Tenggara Timur|-10.17|123.60
Banda Aceh|Aceh|5.55|95.32
Medan|Sumatera Utara|3.59|98.67
Padang|Sumatera Barat|-0.95|100.35
Pekanbaru|Riau|0.51|101.45
Batam|Kepulauan Riau|1.05|104.03
Jambi|Jambi|-1.61|103.61
Palembang|Sumatera Selatan|-2.98|104.76
Bengkulu|Bengkulu|-3.80|102.26
Bandar Lampung|Lampung|-5.43|105.26
Pontianak|Kalimantan Barat|-0.03|109.33
Banjarmasin|Kalimantan Selatan|-3.32|114.59
Balikpapan|Kalimantan Timur|-1.24|116.83
Samarinda|Kalimantan Timur|-0.50|117.15
Makassar|Sulawesi Selatan|-5.15|119.43
Palu|Sulawesi Tengah|-0.90|119.87
Manado|Sulawesi Utara|1.47|124.84
Ambon|Maluku|-3.70|128.18
Jayapura|Papua|-2.53|140.72`.split('\n').map(r=>{const[n,p,la,lo]=r.split('|');return{n,p,la:+la,lo:+lo}});
const GM=Object.fromEntries(G.map(g=>[g.n,g]));
const C=Object.fromEntries(G.map(g=>[g.n,[(g.lo-95)/46*276+2,(6-g.la)/16.5*100+2]]));
const KOTA=G.map(g=>g.n);
const dist=(a,b)=>{const x=GM[a],y=GM[b];if(!x||!y)return 0;const r=Math.PI/180,h=Math.sin((y.la-x.la)*r/2)**2+Math.cos(x.la*r)*Math.cos(y.la*r)*Math.sin((y.lo-x.lo)*r/2)**2;return Math.round(12742*Math.asin(Math.sqrt(h))*1.25)};
const res=t=>{t=String(t||'').trim().toLowerCase();const g=G.find(g=>g.n.toLowerCase()==t)||G.find(g=>g.n.toLowerCase().startsWith(t));return t&&g?g.n:null};
const normHp=t=>{let d=String(t||'').replace(/\D/g,'');if(d.startsWith('62'))d='0'+d.slice(2);return d};
const validHp=d=>/^08\d{8,11}$/.test(d);
const fmtHp=t=>normHp(t).replace(/(\d{4})(?=\d)/g,'$1-')||'-';
let GQ='';
const TODAY='2026-10-01';
const S={
cust:[{id:1,nama:'PT Sinar Pangan',kota:'Jakarta',hp:'0812-1111-2222'},{id:2,nama:'CV Mitra Tekstil',kota:'Bandung',hp:'0813-3333-4444'}],
drv:[{id:1,nama:'Budi Santoso',hp:'0857-1000-2000',sim:'B2 Umum'},{id:2,nama:'Agus Pratama',hp:'0857-3000-4000',sim:'B2 Umum'},{id:3,nama:'Rudi Hartono',hp:'0857-5000-6000',sim:'B2 Umum'}],
trk:[{id:1,plat:'B 9123 KXA',jenis:'Engkel Box',kap:2500,tarif:6500,drv:1,st:'Tersedia'},{id:2,plat:'D 8841 ABC',jenis:'CDD Box',kap:5000,tarif:8500,drv:2,st:'Bertugas'},{id:3,plat:'B 9456 UYT',jenis:'Tronton',kap:12000,tarif:14000,drv:3,st:'Bertugas'},{id:4,plat:'L 9020 FW',jenis:'Trailer',kap:25000,tarif:20000,drv:0,st:'Servis'}],
ord:[],exp:[{id:1,tgl:'2026-09-29',kat:'BBM',trk:3,jml:1850000,ket:'Solar Jakarta-Semarang'},{id:2,tgl:'2026-09-28',kat:'Tol',trk:1,jml:240000,ket:'Tol Bandung-Yogyakarta'}],seq:1};
const gC=i=>S.cust.find(x=>x.id==i),gD=i=>S.drv.find(x=>x.id==i),gT=i=>S.trk.find(x=>x.id==i);
const dN=i=>gD(i)?gD(i).nama:'Belum ada sopir';
function mk(cust,asal,tuj,brg,berat,trk,tgl,st,prog){const d=dist(asal,tuj),t=gT(trk);S.ord.push({id:S.seq++,cust,asal,tuj,brg,berat,trk,tgl,st,prog,jarak:d,biaya:d*t.tarif})}
mk(1,'Jakarta','Semarang','Beras 8 ton',8000,3,'2026-09-30','Dalam perjalanan',.35);
mk(2,'Bandung','Yogyakarta','Kain 1,8 ton',1800,1,'2026-09-28','Terkirim',1);
mk(1,'Jakarta','Bandung','Minuman 4 ton',4000,2,TODAY,'Dijadwalkan',0);
S.drv.forEach(d=>{d.hp=normHp(d.hp);d.st='Aktif';d.exp='2028-03-15';d.alm='-'});S.drv[2].exp='2026-11-10';
S.ord[1].sel={tgl:'2026-09-29',penerima:'Dewi (gudang)',kg:1800,kondisi:'Baik',cat:''};
S.akun=[{uid:'admin',nama:'Administrator',role:'Admin',pw:'admin123',drv:0,aktif:true},{uid:'operator1',nama:'Sari Operator',role:'Operator',pw:'operator123',drv:0,aktif:true},{uid:'budi',nama:'Budi Santoso',role:'Sopir',pw:'sopir123',drv:1,aktif:true}];
S.wa=[];
S.hbbm={'Biosolar':6800,'Dexlite':13500,'Pertamina Dex':14500};
S.trip=[{oid:2,jenis:'Biosolar',pp:1,liter:44,harga:6800,sopir:450000,makan:150000,tol:180000,nontol:40000,kawal:0,pungli:50000,ket:'Contoh data'}];
const tripTot=t=>t.sopir+t.makan+t.liter*t.harga+t.tol+t.nontol+t.kawal+t.pungli;
S.rute={'Jakarta|Bandung':2500000,'Bandung|Yogyakarta':3000000};
const routePrice=(a,u)=>S.rute[a+'|'+u]??S.rute[u+'|'+a]??null;
const kode=o=>'ORD-'+String(o.id).padStart(3,'0');
const bc=s=>({'Dalam perjalanan':'run','Terkirim':'ok','Dibatalkan':'no','Dijadwalkan':'pl','Tiba di tujuan':'run'}[s]||'');
const badge=s=>`<span class="bd ${bc(s)}">${esc(s)}</span>`;
function toast(m){const t=$('#toast');t.textContent=m;t.classList.add('on');clearTimeout(toast.t);toast.t=setTimeout(()=>t.classList.remove('on'),2200)}
function fin(){const rev=S.ord.filter(o=>o.st=='Terkirim').reduce((a,o)=>a+o.biaya,0),cost=S.exp.reduce((a,e)=>a+e.jml,0)+S.trip.reduce((a,t)=>a+tripTot(t),0);return{rev,cost,laba:rev-cost}}
const tbl=(h,r,e='Belum ada data.')=>r.length?`<div class="tw"><table><thead><tr>${h.map(x=>`<th>${x}</th>`).join('')}</tr></thead><tbody>${r.map(x=>`<tr>${x.map(c=>`<td>${c}</td>`).join('')}</tr>`).join('')}</tbody></table></div>`:`<p class="sub">${e}</p>`;
const opt=(a,f)=>a.map(f).join('');
const head=(t,s)=>`<h1>${t}</h1><p class="sub">${s}</p>`;
function freeTrk(id){const t=gT(id);if(t&&t.st=='Bertugas')t.st='Tersedia'}
function start(id){const o=S.ord.find(x=>x.id==id);o.st='Dalam perjalanan';toast(kode(o)+' berangkat');render()}
function cancel(id){const o=S.ord.find(x=>x.id==id);o.st='Dibatalkan';freeTrk(o.trk);toast(kode(o)+' dibatalkan');render()}
function servis(id){const t=gT(id);if(t.st=='Bertugas')return toast('Truk sedang bertugas');t.st=t.st=='Servis'?'Tersedia':'Servis';render()}

const V={
dash(){const f=fin(),ak=S.ord.filter(o=>o.st=='Dalam perjalanan').length,tv=S.trk.filter(t=>t.st=='Tersedia').length;
return head('Dashboard','Ringkasan operasional pengiriman hari ini.')+`<div class="grid k4">
<div class="card kpi a"><b>${ak}</b><span>Pengiriman berjalan</span></div>
<div class="card kpi b"><b>${tv} / ${S.trk.length}</b><span>Truk tersedia</span></div>
<div class="card kpi g"><b>${rp(f.rev)}</b><span>Pendapatan terkirim</span></div>
<div class="card kpi"><b style="color:${f.laba<0?'var(--bad)':'var(--ok)'}">${rp(f.laba)}</b><span>Laba bersih</span></div></div>
<div class="card"><h2>Pesanan terbaru</h2>${tbl(['Kode','Pelanggan','Rute','Status','Progres'],S.ord.filter(mine).slice(-5).reverse().map(o=>[kode(o),esc(gC(o.cust).nama),`${o.asal} - ${o.tuj}`,badge(o.st),`<div class="bar"><i style="width:${o.prog*100}%"></i></div>`]))}</div>
<div class="card"><h2>Status armada</h2>${tbl(['Plat','Jenis','Sopir','Status'],S.trk.map(t=>[esc(t.plat),esc(t.jenis),esc(dN(t.drv)),`<span class="bd ${t.st=='Tersedia'?'ok':t.st=='Bertugas'?'run':'no'}">${t.st}</span>`]))}</div>`},

ord(){return head('Pesanan','Buat pesanan baru. Pilihan truk menyesuaikan berat muatan dan ketersediaan armada.')+`
${doneForm()}<div ${isS()?'hidden':''}><div class="card"><h2>Harga rute</h2><form onsubmit="saveRute(event)">
${acField('r-asal','Kota asal (ketik untuk mencari)','Jakarta')}
${acField('r-tuj','Kota tujuan (ketik untuk mencari)','Surabaya')}
<label>Harga rute (Rp)<input id="r-harga" type="number" min="1" required></label>
<button class="btn">Simpan harga rute</button></form>
<div style="margin-top:12px">${tbl(['Rute','Jarak','Harga rute','Aksi'],Object.entries(S.rute).map(([k,v])=>{const[a,u]=k.split('|');return[`${a} - ${u}`,dist(a,u)+' km',rp(v),ab('rute',k)]}),'Belum ada harga rute. Harga pesanan dihitung dari tarif per km truk.')}</div></div>
<div class="card"><h2>Pesanan baru</h2><form onsubmit="addOrder(event)">
<label>Pelanggan<select id="o-cust">${opt(S.cust,c=>`<option value="${c.id}">${esc(c.nama)}</option>`)}</select></label>
${acField('o-asal','Kota asal (ketik untuk mencari)','Jakarta')}
${acField('o-tuj','Kota tujuan (ketik untuk mencari)','Surabaya')}
<label>Alamat jemput (detail)<input id="o-almA" placeholder="Jalan, gudang, nomor"></label>
<label>Alamat antar (detail)<input id="o-almT" placeholder="Jalan, gudang, nomor"></label>
<label>Jenis barang<input id="o-brg" required placeholder="Contoh: Beras"></label>
<label>Berat (kg)<input id="o-berat" type="number" min="1" value="1000" required oninput="fillTrk()"></label>
<label>Truk dan sopir<select id="o-trk" onchange="est()"></select></label>
<label>Harga rute (Rp)<input id="o-harga" type="number" min="1" required oninput="est(1)"></label>
<label>Tanggal kirim<input id="o-tgl" type="date" value="${TODAY}" required></label>
<div class="est full" id="est"></div><button class="btn">Simpan pesanan</button></form></div></div>
<div class="card"><h2>Daftar pesanan</h2>${tbl(['Kode','Pelanggan','Rute','Barang','Truk / Sopir','Jarak','Harga','Status','Penerima','Aksi'],S.ord.filter(mine).reverse().map(o=>{const t=gT(o.trk);return[kode(o),esc(gC(o.cust).nama),`${o.asal} - ${o.tuj}`+(o.almA||o.almT?`<br><small>${esc(o.almA||'-')} &rarr; ${esc(o.almT||'-')}</small>`:''),esc(o.brg),`${esc(t.plat)} / ${esc(dN(t.drv))}<br><small>${fmtHp((gD(t.drv)||{}).hp)}</small>`,o.jarak+' km',rp(o.biaya),badge(o.st),esc(o.sel?o.sel.penerima+' ('+o.sel.kondisi+')':'-'),(o.st=='Dalam perjalanan'||o.st=='Tiba di tujuan'?`<button class="btn s" onclick="selesai(${o.id})">Selesaikan</button> `:'')+(o.st=='Dijadwalkan'?`<button class="btn s" onclick="start(${o.id})">Berangkat</button> `:'')+(!isS()&&(o.st=='Dijadwalkan'||o.st=='Dalam perjalanan')?`<button class="btn s d" onclick="cancel(${o.id})">Batalkan</button>`:'')+(isS()?'':' '+ab('ord',o.id))]}))}</div>`},

trk(){return head('Armada','Kelola truk. Sopir yang ditugaskan di sini otomatis terpasang saat membuat pesanan.')+`
<div class="card"><h2>Tambah truk</h2><form onsubmit="addTrk(event)">
<label>Plat nomor<input id="t-plat" required placeholder="B 1234 XYZ"></label>
<label>Jenis<select id="t-jenis" onchange="presetT()"><option>Engkel Box</option><option>CDD Box</option><option>Tronton</option><option>Trailer</option></select></label>
<label>Kapasitas (kg)<input id="t-kap" type="number" min="1" value="2500" required></label>
<label>Tarif per km (Rp)<input id="t-tarif" type="number" min="1" value="6500" required></label>
<label>Sopir<select id="t-drv"><option value="0">Belum ada sopir</option>${opt(S.drv.filter(d=>d.st=='Aktif'),d=>`<option value="${d.id}">${esc(d.nama)}</option>`)}</select></label>
<button class="btn">Simpan truk</button></form></div>
<div class="card"><h2>Daftar truk</h2>${tbl(['Plat','Jenis','Kapasitas','Tarif/km','Sopir','Status','Aksi'],S.trk.map(t=>[esc(t.plat),esc(t.jenis),t.kap.toLocaleString('id-ID')+' kg',rp(t.tarif),esc(dN(t.drv)),`<span class="bd ${t.st=='Tersedia'?'ok':t.st=='Bertugas'?'run':'no'}">${t.st}</span>`,`<button class="btn s" onclick="servis(${t.id})">${t.st=='Servis'?'Selesai servis':'Masuk servis'}</button> ${ab('trk',t.id)}`]))}</div>`},

usr(){return head('Pengguna','Data pelanggan dan sopir yang dipakai di pesanan dan armada.')+`<div class="grid c2">
<div><div class="card"><h2>Tambah pelanggan</h2><form onsubmit="addCust(event)">
<label>Nama<input id="c-nama" required></label><label>Kota<select id="c-kota">${opt(KOTA,k=>`<option>${k}</option>`)}</select></label>
<label>No. HP<input id="c-hp" required inputmode="tel"></label><button class="btn">Simpan pelanggan</button></form></div>
<div class="card"><h2>Pelanggan</h2>${tbl(['Nama','Kota','HP','Aksi'],S.cust.map(c=>[esc(c.nama),c.kota,fmtHp(c.hp),ab('cust',c.id)]))}</div></div>
<div><div class="card"><h2>Tambah sopir</h2><form onsubmit="addDrv(event)">
<label>Nama<input id="d-nama" required></label><label>No. seluler (dasar pelacakan)<input id="d-hp" required inputmode="tel" placeholder="0857-1000-2000"></label>
<label>Jenis SIM<select id="d-sim"><option>B1 Umum</option><option>B2 Umum</option></select></label>
<label>SIM berlaku sampai<input id="d-exp" type="date" value="2028-10-01" required></label>
<label>Alamat<input id="d-alm"></label>
<label>Status<select id="d-st"><option>Aktif</option><option>Cuti</option></select></label>
<label>Tugaskan ke truk<select id="d-trk"><option value="0">Belum ditugaskan</option>${opt(S.trk.filter(t=>!t.drv),t=>`<option value="${t.id}">${esc(t.plat)}, ${esc(t.jenis)}</option>`)}</select></label>
<button class="btn">Simpan sopir</button></form></div>
<div class="card"><h2>Sopir</h2>${tbl(['Nama','SIM','Berlaku','HP','Truk','Status','User ID','Aksi'],S.drv.map(d=>{const t=S.trk.find(x=>x.drv==d.id);return[esc(d.nama),d.sim,d.exp+(d.exp<'2026-12-01'?' (segera habis)':''),fmtHp(d.hp),t?esc(t.plat):'-',`<span class="bd ${d.st=='Aktif'?'ok':'no'}">${d.st}</span>`,esc((S.akun.find(a=>a.drv==d.id)||{}).uid||'-'),`<button class="btn s" onclick="togDrv(${d.id})">${d.st=='Cuti'?'Aktifkan':'Cuti'}</button> <button class="btn s" onclick="GQ='${d.hp}';go('gps')">Lacak</button> ${ab('drv',d.id)}`]}))}</div></div></div>`},

gps(){const act=S.ord.filter(o=>(o.st=='Dalam perjalanan'||o.st=='Tiba di tujuan')&&mine(o));
const lines=act.map(o=>{const a=C[o.asal],b=C[o.tuj];return`<line x1="${a[0]}" y1="${a[1]}" x2="${b[0]}" y2="${b[1]}" stroke="var(--mut)" stroke-dasharray="3 3"/>`}).join('');
const used=[...new Set(act.flatMap(o=>[o.asal,o.tuj]))],dots=KOTA.map(k=>`<circle cx="${C[k][0]}" cy="${C[k][1]}" r="1.6" fill="var(--mut)" opacity=".5"/>`).join('')+used.map(k=>`<circle cx="${C[k][0]}" cy="${C[k][1]}" r="3" fill="var(--ink)"/><text x="${C[k][0]}" y="${C[k][1]-6}" font-size="7" text-anchor="middle" fill="var(--ink)">${k}</text>`).join('');
const q=normHp(GQ),td=GQ?S.drv.find(d=>d.hp==q&&(!isS()||d.id==ME.drv)):null,tt=td&&S.trk.find(x=>x.drv==td.id),tO=td&&act.find(o=>gT(o.trk).drv==td.id);
let hasil='';if(GQ&&!td)hasil=`<p class="sub" style="margin:12px 0 0">Nomor ${esc(GQ)} tidak terdaftar sebagai sopir.</p>`;
else if(td){let pos='Sedang tidak bertugas.';if(tO){const a=GM[tO.asal],b=GM[tO.tuj];pos=`Pesanan ${kode(tO)}, ${tO.asal} - ${tO.tuj}, ${badge(tO.st)}. Posisi terakhir <b>${(a.la+(b.la-a.la)*tO.prog).toFixed(4)}, ${(a.lo+(b.lo-a.lo)*tO.prog).toFixed(4)}</b> (${Math.round(tO.prog*100)}% perjalanan, sisa ${Math.round(tO.jarak*(1-tO.prog))} km).`}
hasil=`<div style="margin-top:12px"><b>${esc(td.nama)}</b>, ${fmtHp(td.hp)} <span class="bd ${td.st=='Aktif'?'ok':'no'}">${td.st}</span><br>Truk: ${tt?esc(tt.plat)+' ('+esc(tt.jenis)+')':'belum ada'}.<br>${pos}</div>`}
const cari=`<div class="card"><h2>Lacak berdasarkan nomor seluler</h2><form onsubmit="cariHp(event)"><label>Nomor seluler sopir<input id="g-hp" type="tel" inputmode="tel" value="${esc(GQ)}" oninput="GQ=this.value" placeholder="0857-1000-2000 atau +62857..."></label><div><button class="btn">Lacak</button> ${GQ?`<button type="button" class="btn s" onclick="GQ='';render()">Hapus</button>`:''}</div></form>${hasil}</div>`;
const tr=act.map(o=>{const a=C[o.asal],b=C[o.tuj],x=a[0]+(b[0]-a[0])*o.prog,y=a[1]+(b[1]-a[1])*o.prog;return(o===tO?`<circle cx="${x}" cy="${y}" r="9" fill="none" stroke="var(--acc)" stroke-width="1.5"/>`:'')+`<circle cx="${x}" cy="${y}" r="5" fill="var(--acc)" stroke="var(--ink)" stroke-width="1.5"/>`}).join('');
return head('Pelacakan GPS','Setiap sopir dilacak lewat nomor selulernya. Posisi diperbarui otomatis setiap 2 detik (simulasi).')+cari+`<div class="card"><svg class="map" viewBox="0 0 280 104" role="img" aria-label="Peta posisi truk">${lines}${dots}${tr}</svg></div>
<div class="card"><h2>Truk di jalan</h2>${tbl(['Kode','Truk','Sopir','No. seluler','Rute','Posisi','Sisa jarak'],act.map(o=>{const t=gT(o.trk);return[kode(o),esc(t.plat),esc(dN(t.drv)),`<button class="btn s" onclick="GQ='${(gD(t.drv)||{}).hp}';render()">${fmtHp((gD(t.drv)||{}).hp)}</button>`,`${o.asal} - ${o.tuj}`,`<div class="bar"><i style="width:${o.prog*100}%"></i></div>`,Math.round(o.jarak*(1-o.prog))+' km']}),'Tidak ada truk yang sedang berjalan. Mulai dari menu Pesanan.')}</div>`},

fin(){const f=fin();return head('Keuangan','Pendapatan diakui saat pesanan berstatus Terkirim. Pengeluaran mencakup biaya perjalanan dari menu Biaya Perjalanan dan pengeluaran per truk.')+`<div class="grid k4">
<div class="card kpi g"><b>${rp(f.rev)}</b><span>Pendapatan</span></div><div class="card kpi a"><b>${rp(f.cost)}</b><span>Pengeluaran</span></div>
<div class="card kpi"><b style="color:${f.laba<0?'var(--bad)':'var(--ok)'}">${rp(f.laba)}</b><span>Laba bersih</span></div></div>
<div class="card"><h2>Catat pengeluaran</h2><form onsubmit="addExp(event)">
<label>Tanggal<input id="e-tgl" type="date" value="${TODAY}" required></label>
<label>Kategori<select id="e-kat"><option>BBM</option><option>Tol</option><option>Servis</option><option>Gaji sopir</option><option>Lainnya</option></select></label>
<label>Truk<select id="e-trk">${opt(S.trk,t=>`<option value="${t.id}">${esc(t.plat)}</option>`)}</select></label>
<label>Jumlah (Rp)<input id="e-jml" type="number" min="1" required></label>
<label>Keterangan<input id="e-ket"></label><button class="btn">Simpan pengeluaran</button></form></div>
<div class="card"><h2>Pengeluaran</h2>${tbl(['Tanggal','Kategori','Truk','Jumlah','Keterangan','Aksi'],S.exp.slice().reverse().map(e=>[e.tgl,e.kat,esc(gT(e.trk).plat),rp(e.jml),esc(e.ket||'-'),ab('exp',e.id)]))}</div>
<div class="card"><h2>Selisih tagihan dan biaya perjalanan</h2>${tbl(['Kode','Rute','Status','Tagihan','Biaya perjalanan','Selisih'],S.ord.filter(o=>o.st!='Dibatalkan').map(o=>{const t=S.trip.find(x=>x.oid==o.id),b=t?tripTot(t):0;return[kode(o),`${o.asal} - ${o.tuj}`,badge(o.st),rp(o.biaya),rp(b),rp(o.biaya-b)]}))}</div>
<div class="card"><h2>Pendapatan per pesanan</h2>${tbl(['Kode','Pelanggan','Rute','Tagihan'],S.ord.filter(o=>o.st=='Terkirim').map(o=>[kode(o),esc(gC(o.cust).nama),`${o.asal} - ${o.tuj}`,rp(o.biaya)]),'Belum ada pesanan terkirim.')}</div>`},

biaya(){const os=S.ord.filter(o=>o.st!='Dibatalkan'),hk=Object.keys(S.hbbm);
return head('Biaya Perjalanan','Catat biaya operasional per pesanan: sopir, BBM, tol, jalan non-tol, kawalan, dan biaya tak resmi. Totalnya masuk ke Keuangan.')+`
<div class="card"><h2>Harga BBM per liter</h2><form onsubmit="saveBbm(event)">${hk.map((k,i)=>`<label>${k} (Rp)<input type="number" min="1" id="h-${i}" value="${S.hbbm[k]}"></label>`).join('')}<button class="btn">Simpan harga</button></form>
<p class="sub" style="margin:8px 0 0">Nilai awal hanya contoh. Ubah sesuai harga SPBU terbaru.</p></div>
<div class="card"><h2>Biaya per pesanan</h2><form onsubmit="saveTrip(event)">
<label>Pesanan<select id="b-ord" onchange="loadTrip()">${opt(os,o=>`<option value="${o.id}">${kode(o)}: ${o.asal} - ${o.tuj}</option>`)}</select></label>
<label>Jenis BBM<select id="b-jenis" onchange="bbmPrice()">${hk.map(k=>`<option>${k}</option>`).join('')}</select></label>
<label>Rute BBM<select id="b-pp" onchange="bbmAuto()"><option value="1">Sekali jalan</option><option value="2">Pulang-pergi</option></select></label>
<label>Liter BBM<input id="b-liter" type="number" min="0" step="0.1" oninput="tot()"></label>
<label>Harga per liter (Rp)<input id="b-harga" type="number" min="0" oninput="tot()"></label>
<label>Upah / uang jalan sopir (Rp)<input id="b-sopir" type="number" min="0" oninput="tot()"></label>
<label>Makan dan inap sopir (Rp)<input id="b-makan" type="number" min="0" oninput="tot()"></label>
<label>Jalan tol (Rp)<input id="b-tol" type="number" min="0" oninput="tot()"></label>
<label>Jalan non-tol: retribusi, jembatan, parkir (Rp)<input id="b-non" type="number" min="0" oninput="tot()"></label>
<label>Kawalan (Rp)<input id="b-kawal" type="number" min="0" oninput="tot()"></label>
<label>Pungli / biaya tak resmi (Rp)<input id="b-pungli" type="number" min="0" oninput="tot()"></label>
<label class="full">Keterangan<input id="b-ket" placeholder="Opsional"></label>
<div class="est full" id="b-tot"></div><button class="btn">Simpan biaya</button></form></div>
<div class="card"><h2>Rekap biaya perjalanan</h2>${tbl(['Kode','Rute','Sopir','BBM','Tol','Non-tol','Kawalan','Pungli','Total','Aksi'],S.trip.map(t=>{const o=S.ord.find(x=>x.id==t.oid);return[kode(o),`${o.asal} - ${o.tuj}`,rp(t.sopir+t.makan),rp(t.liter*t.harga),rp(t.tol),rp(t.nontol),rp(t.kawal),rp(t.pungli),`<b>${rp(tripTot(t))}</b>`,`<button class="btn s" onclick="editTrip(${t.oid})">Edit</button> <button class="btn s d" onclick="delTrip(${t.oid})">Hapus</button>`]}),'Belum ada biaya perjalanan yang dicatat.')}</div>`},

wa(){return head('WhatsApp','Susun pesan penugasan, status, dan tagihan untuk sopir atau pelanggan. Pesan dibuka di WhatsApp dan dikirim dari perangkat Anda.')+`
<div class="card"><h2>Tulis pesan</h2><form onsubmit="return false">
<label>Penerima<select id="w-to" onchange="waUpd()"><optgroup label="Sopir">${S.drv.map(d=>`<option value="d:${d.id}">${esc(d.nama)} (${fmtHp(d.hp)})</option>`).join('')}</optgroup><optgroup label="Pelanggan">${S.cust.map(c=>`<option value="c:${c.id}">${esc(c.nama)} (${fmtHp(c.hp)})</option>`).join('')}</optgroup></select></label>
<label>Pesanan terkait<select id="w-ord" onchange="waMsg()"></select></label>
<label>Jenis pesan<select id="w-tpl" onchange="waMsg()"></select></label>
<label class="full">Isi pesan (bisa diedit)<textarea id="w-msg" oninput="waLink()"></textarea></label>
<div class="full"><a id="w-link" class="btn" style="text-decoration:none;display:inline-block" target="_blank" rel="noopener" onclick="return waGo()">Buka WhatsApp</a> <span id="w-note" class="sub"></span></div></form></div>
<div class="card"><h2>Riwayat pesan</h2><div id="w-log">${waLogHtml()}</div></div>`},

akun(){return head('Akun & User ID','Buat User ID untuk operator dan sopir. Sopir hanya melihat pesanan dari truknya.')+`<div class="card"><h2>Tambah user</h2><form onsubmit="addAkun(event)">
<label>User ID<input id="a-uid" required pattern="[a-z0-9._-]{4,20}" title="4-20 karakter: huruf kecil, angka, titik, garis bawah, atau strip" autocomplete="off"></label>
<label>Nama lengkap<input id="a-nama" required></label>
<label>Peran<select id="a-role" onchange="$('#a-drv').disabled=this.value!='Sopir'"><option>Operator</option><option>Sopir</option><option>Admin</option></select></label>
<label>Data sopir<select id="a-drv" disabled>${opt(S.drv,d=>`<option value="${d.id}">${esc(d.nama)}</option>`)}</select></label>
<label>Kata sandi<input id="a-pw" type="password" minlength="6" required autocomplete="new-password"></label>
<button class="btn">Simpan user</button></form></div>
<div class="card"><h2>Daftar user</h2>${tbl(['User ID','Nama','Peran','Data sopir','Status','Aksi'],S.akun.map(a=>[esc(a.uid),esc(a.nama),a.role,a.role=='Sopir'?esc(dN(a.drv)):'-',`<span class="bd ${a.aktif?'ok':'no'}">${a.aktif?'Aktif':'Nonaktif'}</span>`,a.uid==ME.uid?'(akun Anda)':`<button class="btn s" onclick="togAkun('${a.uid}')">${a.aktif?'Nonaktifkan':'Aktifkan'}</button> <button class="btn s" onclick="edt('akun','${a.uid}')">Edit</button> <button class="btn s d" onclick="delAkun('${a.uid}')">Hapus</button>`]))}</div>`},

rep(){const r=repData();return head('Laporan','Pilih jenis laporan untuk melihat datanya dalam tabel.')+`
<div class="card"><form onsubmit="return false"><label>Jenis laporan<select id="r-jenis" onchange="RJ=this.value;render()">${['Pesanan','Keuangan','Armada','Sopir','Biaya Perjalanan'].map(j=>`<option ${j==RJ?'selected':''}>${j}</option>`).join('')}</select></label></form></div>
${RJ=='Keuangan'?marginCard():''}<div class="card"><h2>Laporan ${RJ.toLowerCase()}</h2>${tbl(r.h,r.rows.map(x=>x.map(c=>typeof c=='number'?c.toLocaleString('id-ID'):esc(c))))}</div>`}
};
let RJ='Pesanan';
function marginCard(){const os=S.ord.filter(o=>o.st!='Dibatalkan'),pr=(m,h)=>(m/h*100).toFixed(1).replace('.',',')+'%';let H=0,B=0;
const rows=os.map(o=>{const t=S.trip.find(x=>x.oid==o.id),base=[kode(o),o.tgl,esc(gC(o.cust).nama),`${o.asal} - ${o.tuj}`,badge(o.st),rp(o.biaya)];
if(!t)return[...base,'Belum diisi','-','-'];
const b=tripTot(t),m=o.biaya-b;H+=o.biaya;B+=b;
return[...base,rp(b),`<b style="color:${m<0?'var(--bad)':'var(--ok)'}">${rp(m)}</b>`,pr(m,o.biaya)]});
if(H)rows.push(['<b>Total</b>','','','','',`<b>${rp(H)}</b>`,`<b>${rp(B)}</b>`,`<b>${rp(H-B)}</b>`,`<b>${pr(H-B,H)}</b>`]);
return`<div class="card"><h2>Margin biaya perjalanan terhadap harga pesanan</h2>${tbl(['Kode','Tanggal','Pelanggan','Rute','Status','Harga pesanan','Biaya perjalanan','Margin','Margin (%)'],rows)}<p class="sub" style="margin:8px 0 0">Margin = harga pesanan dikurangi biaya perjalanan. Total hanya menghitung pesanan yang biayanya sudah diisi di menu Biaya Perjalanan.</p></div>`}
function repData(){
if(RJ=='Pesanan')return{h:['Kode','Tanggal','Pelanggan','Asal','Tujuan','Barang','Berat (kg)','Truk','Sopir','No. seluler sopir','Jarak (km)','Biaya (Rp)','Status','Penerima','Kondisi','Tgl diterima'],rows:S.ord.map(o=>{const t=gT(o.trk);return[kode(o),o.tgl,gC(o.cust).nama,o.asal,o.tuj,o.brg,o.berat,t.plat,dN(t.drv),fmtHp((gD(t.drv)||{}).hp),o.jarak,o.biaya,o.st,o.sel?o.sel.penerima:'-',o.sel?o.sel.kondisi:'-',o.sel?o.sel.tgl:'-']})};
if(RJ=='Keuangan')return{h:['Tanggal','Jenis','Keterangan','Jumlah (Rp)'],rows:[...S.ord.filter(o=>o.st=='Terkirim').map(o=>[o.tgl,'Pendapatan',kode(o),o.biaya]),...S.exp.map(e=>[e.tgl,'Pengeluaran',e.kat+' '+(e.ket||''),-e.jml])]};
if(RJ=='Biaya Perjalanan')return{h:['Kode','Rute','Jenis BBM','Liter','Harga/liter','BBM','Upah sopir','Makan dan inap','Tol','Non-tol','Kawalan','Pungli','Total','Keterangan'],rows:S.trip.map(t=>{const o=S.ord.find(x=>x.id==t.oid);return[kode(o),o.asal+' - '+o.tuj,t.jenis,t.liter,t.harga,t.liter*t.harga,t.sopir,t.makan,t.tol,t.nontol,t.kawal,t.pungli,tripTot(t),t.ket||'-']})};
if(RJ=='Sopir')return{h:['Nama','HP','SIM','SIM berlaku','Alamat','Status','Truk'],rows:S.drv.map(d=>{const t=S.trk.find(x=>x.drv==d.id);return[d.nama,fmtHp(d.hp),d.sim,d.exp,d.alm||'-',d.st,t?t.plat:'-']})};
return{h:['Plat','Jenis','Kapasitas (kg)','Tarif/km (Rp)','Sopir','Status','Total pesanan'],rows:S.trk.map(t=>[t.plat,t.jenis,t.kap,t.tarif,dN(t.drv),t.st,S.ord.filter(o=>o.trk==t.id).length])}}

function fillTrk(){const b=+$('#o-berat').value||0,sel=$('#o-trk'),cur=sel.value;
const ok=S.trk.filter(t=>t.st=='Tersedia'&&t.kap>=b&&gD(t.drv)&&gD(t.drv).st=='Aktif');
sel.innerHTML=ok.length?opt(ok,t=>`<option value="${t.id}">${esc(t.plat)}, ${esc(t.jenis)} ${t.kap}kg, ${esc(dN(t.drv))}</option>`):'<option value="">Tidak ada truk dengan sopir aktif yang cocok</option>';
if(ok.some(t=>t.id==cur))sel.value=cur;est()}
function est(keep){const a=res($('#o-asal').value),u=res($('#o-tuj').value),t=gT($('#o-trk').value),el=$('#est'),h=$('#o-harga');
if(!t||!a||!u||a==u){el.textContent='Pilih kota asal dan tujuan dari saran pencarian (harus berbeda), serta truk yang cocok.';if(!keep)h.value='';return}
const d=dist(a,u),rt=routePrice(a,u),std=rt??d*t.tarif;if(!keep)h.value=std;
el.innerHTML=`Jarak sekitar <b>${d} km</b>. ${rt!=null?'Harga rute tersimpan':'Belum ada harga rute, dihitung dari tarif truk'}: <b>${rp(std)}</b>. Harga pesanan: <b>${rp(+h.value||0)}</b>. Estimasi tiba ${Math.ceil(d/50)} jam.`}
function saveRute(e){e.preventDefault();const a=res($('#r-asal').value),u=res($('#r-tuj').value);if(!a||!u)return toast('Pilih kota dari daftar saran');if(a==u)return toast('Kota asal dan tujuan harus berbeda');
delete S.rute[u+'|'+a];S.rute[a+'|'+u]=+$('#r-harga').value;toast('Harga rute disimpan');render()}
function delRute(k){ask('Hapus harga rute '+k.replace('|',' - ')+'?',()=>{delete S.rute[k];toast('Harga rute dihapus')})}
function addOrder(e){e.preventDefault();const a=res($('#o-asal').value),u=res($('#o-tuj').value),t=$('#o-trk').value;
if(!a||!u)return toast('Pilih kota asal dan tujuan dari daftar saran');if(a==u)return toast('Kota asal dan tujuan harus berbeda');if(!t)return toast('Tidak ada truk yang cocok untuk berat ini');
if(!(+$('#o-harga').value>0))return toast('Isi harga rute');
mk(+$('#o-cust').value,a,u,$('#o-brg').value,+$('#o-berat').value,+t,$('#o-tgl').value,'Dijadwalkan',0);S.ord[S.ord.length-1].biaya=+$('#o-harga').value;Object.assign(S.ord[S.ord.length-1],{almA:$('#o-almA').value,almT:$('#o-almT').value});
gT(t).st='Bertugas';toast('Pesanan disimpan');render()}
const PRE={'Engkel Box':[2500,6500],'CDD Box':[5000,8500],'Tronton':[12000,14000],'Trailer':[25000,20000]};
function presetT(){const p=PRE[$('#t-jenis').value];$('#t-kap').value=p[0];$('#t-tarif').value=p[1]}
function addTrk(e){e.preventDefault();S.trk.push({id:Math.max(...S.trk.map(t=>t.id))+1,plat:$('#t-plat').value.toUpperCase(),jenis:$('#t-jenis').value,kap:+$('#t-kap').value,tarif:+$('#t-tarif').value,drv:+$('#t-drv').value,st:'Tersedia'});toast('Truk disimpan');render()}
function addCust(e){e.preventDefault();S.cust.push({id:Math.max(0,...S.cust.map(x=>x.id))+1,nama:$('#c-nama').value,kota:$('#c-kota').value,hp:$('#c-hp').value});toast('Pelanggan disimpan');render()}
function addDrv(e){e.preventDefault();const hp=normHp($('#d-hp').value);if(!validHp(hp))return toast('Nomor seluler tidak valid. Contoh: 0857-1000-2000');if(S.drv.some(d=>d.hp==hp))return toast('Nomor seluler sudah dipakai sopir lain');const id=Math.max(...S.drv.map(d=>d.id))+1;S.drv.push({id,nama:$('#d-nama').value,hp,sim:$('#d-sim').value,exp:$('#d-exp').value,alm:$('#d-alm').value,st:$('#d-st').value});const t=gT($('#d-trk').value);if(t)t.drv=id;toast('Sopir disimpan');render()}
function togDrv(id){const d=gD(id),t=S.trk.find(x=>x.drv==id);if(t&&t.st=='Bertugas')return toast('Sopir sedang bertugas');d.st=d.st=='Cuti'?'Aktif':'Cuti';render()}
let DONE=null;
function selesai(id){DONE=id;render();window.scrollTo(0,0)}
function tutup(){DONE=null;render()}
function doneForm(){const o=S.ord.find(x=>x.id==DONE);if(!o)return'';
return `<div class="card" style="border-color:var(--acc)"><h2>Selesaikan ${kode(o)}: ${o.asal} - ${o.tuj}</h2><form onsubmit="finishOrder(event)">
<label>Nama penerima<input id="f-pen" required></label>
<label>Tanggal diterima<input id="f-tgl" type="date" value="${TODAY}" required></label>
<label>Berat diterima (kg)<input id="f-kg" type="number" min="0" value="${o.berat}" required></label>
<label>Kondisi barang<select id="f-kon"><option>Baik</option><option>Rusak sebagian</option><option>Rusak</option></select></label>
<label class="full">Catatan<input id="f-cat" placeholder="Opsional"></label>
<div class="full"><button class="btn">Simpan penyelesaian</button> <button type="button" class="btn s" onclick="tutup()">Batal</button></div></form></div>`}
function finishOrder(e){e.preventDefault();const o=S.ord.find(x=>x.id==DONE);o.sel={tgl:$('#f-tgl').value,penerima:$('#f-pen').value,kg:+$('#f-kg').value,kondisi:$('#f-kon').value,cat:$('#f-cat').value};o.st='Terkirim';o.prog=1;freeTrk(o.trk);DONE=null;toast(kode(o)+' selesai, pendapatan tercatat');render()}
function addExp(e){e.preventDefault();S.exp.push({id:Math.max(0,...S.exp.map(x=>x.id))+1,tgl:$('#e-tgl').value,kat:$('#e-kat').value,trk:+$('#e-trk').value,jml:+$('#e-jml').value,ket:$('#e-ket').value});toast('Pengeluaran disimpan');render()}

const KML={'Engkel Box':8,'CDD Box':6,'Tronton':4,'Trailer':3};
const nv=i=>+$('#'+i).value||0;
function loadTrip(){const el=$('#b-ord');if(!el||!el.value)return;const t=S.trip.find(x=>x.oid==el.value),set=(i,v)=>{$('#'+i).value=v};
if(t){set('b-jenis',t.jenis);set('b-pp',t.pp||1);set('b-liter',t.liter);set('b-harga',t.harga);set('b-sopir',t.sopir);set('b-makan',t.makan);set('b-tol',t.tol);set('b-non',t.nontol);set('b-kawal',t.kawal);set('b-pungli',t.pungli);set('b-ket',t.ket||'')}
else{['b-sopir','b-makan','b-tol','b-non','b-kawal','b-pungli'].forEach(i=>set(i,0));set('b-ket','');set('b-pp',1);set('b-harga',S.hbbm[$('#b-jenis').value]);bbmAuto()}
tot()}
function bbmPrice(){$('#b-harga').value=S.hbbm[$('#b-jenis').value];tot()}
function bbmAuto(){const o=S.ord.find(x=>x.id==$('#b-ord').value);if(!o)return;$('#b-liter').value=(o.jarak*(+$('#b-pp').value)/(KML[gT(o.trk).jenis]||5)).toFixed(1);tot()}
function tot(){const o=S.ord.find(x=>x.id==$('#b-ord').value);if(!o)return;const l=nv('b-liter')*nv('b-harga'),all=l+['b-sopir','b-makan','b-tol','b-non','b-kawal','b-pungli'].reduce((a,i)=>a+nv(i),0);
$('#b-tot').innerHTML=`BBM <b>${rp(l)}</b> (${nv('b-liter')} liter). Total biaya perjalanan <b>${rp(all)}</b>. Tagihan ${rp(o.biaya)}, selisih <b>${rp(o.biaya-all)}</b>.`}
function saveTrip(e){e.preventDefault();const oid=+$('#b-ord').value;if(!oid)return toast('Belum ada pesanan');
S.trip=S.trip.filter(x=>x.oid!=oid);S.trip.push({oid,jenis:$('#b-jenis').value,pp:+$('#b-pp').value,liter:nv('b-liter'),harga:nv('b-harga'),sopir:nv('b-sopir'),makan:nv('b-makan'),tol:nv('b-tol'),nontol:nv('b-non'),kawal:nv('b-kawal'),pungli:nv('b-pungli'),ket:$('#b-ket').value});toast('Biaya perjalanan disimpan');render()}
function delTrip(id){ask('Hapus catatan biaya perjalanan untuk pesanan '+kode(S.ord.find(x=>x.id==id))+'?',()=>{S.trip=S.trip.filter(x=>x.oid!=id);toast('Biaya dihapus')})}
function editTrip(id){BO=id;render();window.scrollTo(0,0)}
function saveBbm(e){e.preventDefault();Object.keys(S.hbbm).forEach((k,i)=>{S.hbbm[k]=nv('h-'+i)});toast('Harga BBM disimpan');render()}
const ACI={};
function acField(id,label,def){return`<label>${label}<div class="ac"><input id="${id}" value="${def}" autocomplete="off" role="combobox" aria-autocomplete="list" placeholder="Ketik nama kota" oninput="acIn('${id}');${id[0]=='o'?'est()':''}" onfocus="acIn('${id}')" onblur="setTimeout(()=>acHide('${id}'),150)" onkeydown="acKey(event,'${id}')"><ul class="acl" id="${id}-l" role="listbox" hidden></ul></div></label>`}
function acIn(id){const q=$('#'+id).value.trim().toLowerCase(),l=$('#'+id+'-l'),has=(g,f)=>g[f].toLowerCase().includes(q);
const hit=q?G.filter(g=>g.n.toLowerCase().startsWith(q)).concat(G.filter(g=>!g.n.toLowerCase().startsWith(q)&&(has(g,'n')||has(g,'p')))).slice(0,6):G.slice(0,6);
ACI[id]=-1;l.innerHTML=hit.length?hit.map(g=>`<li role="option" data-n="${g.n}" onmousedown="event.preventDefault();acPick('${id}','${g.n}')"><b>${g.n}</b> <small>${g.p}</small></li>`).join(''):'<li class="none">Kota tidak ditemukan</li>';l.hidden=false}
function acHide(id){const l=$('#'+id+'-l');if(l)l.hidden=true}
function acPick(id,n){$('#'+id).value=n;acHide(id);if(id[0]=='o')est()}
function acKey(e,id){const l=$('#'+id+'-l'),it=[...l.querySelectorAll('li[role=option]')];if(!it.length)return;
if(e.key=='ArrowDown'||e.key=='ArrowUp'){e.preventDefault();ACI[id]=(ACI[id]+(e.key=='ArrowDown'?1:-1)+it.length)%it.length;it.forEach((x,i)=>x.classList.toggle('on',i==ACI[id]))}
else if(e.key=='Enter'&&!l.hidden){e.preventDefault();acPick(id,it[ACI[id]>=0?ACI[id]:0].dataset.n)}
else if(e.key=='Escape')acHide(id)}
const WAT={
'Penugasan sopir':{to:'d',f:(o,r)=>`Halo ${r.nama}, ada penugasan baru dari BIMA LOGISTICS.\nPesanan: ${kode(o)}\nRute: ${o.asal} - ${o.tuj}\nJemput: ${o.almA||'-'}\nAntar: ${o.almT||'-'}\nBarang: ${o.brg} (${o.berat} kg)\nTruk: ${gT(o.trk).plat}\nTanggal: ${o.tgl}\nMohon konfirmasi bila sudah menerima pesan ini.`},
'Pengingat keberangkatan':{to:'d',f:(o,r)=>`Halo ${r.nama}, pengingat: pesanan ${kode(o)} berangkat tanggal ${o.tgl} dari ${o.asal} ke ${o.tuj}. Pastikan truk ${gT(o.trk).plat} dan muatan siap.`},
'Minta konfirmasi tiba':{to:'d',f:(o,r)=>`Halo ${r.nama}, apakah pesanan ${kode(o)} sudah tiba di ${o.tuj}? Mohon kabari nama penerima dan kondisi barang.`},
'Info keberangkatan':{to:'c',f:(o,r)=>`Yth. ${r.nama},\nPesanan ${kode(o)} (${o.brg}, ${o.berat} kg) dari ${o.asal} ke ${o.tuj} dijadwalkan berangkat ${o.tgl} dengan truk ${gT(o.trk).plat}.\nSopir: ${dN(gT(o.trk).drv)} (${fmtHp((gD(gT(o.trk).drv)||{}).hp)}).\nTerima kasih, BIMA LOGISTICS.`},
'Status dan posisi':{to:'c',f:(o,r)=>{const a=GM[o.asal],b=GM[o.tuj];return `Yth. ${r.nama},\nStatus pesanan ${kode(o)} (${o.asal} - ${o.tuj}): ${o.st}.`+(o.st=='Dalam perjalanan'?`\nPerjalanan sudah ${Math.round(o.prog*100)}%, sisa sekitar ${Math.round(o.jarak*(1-o.prog))} km.\nPosisi terakhir: ${(a.la+(b.la-a.la)*o.prog).toFixed(4)}, ${(a.lo+(b.lo-a.lo)*o.prog).toFixed(4)}.`:'')+`\nTerima kasih, BIMA LOGISTICS.`}},
'Barang tiba':{to:'c',f:(o,r)=>`Yth. ${r.nama},\nPesanan ${kode(o)} telah tiba di ${o.tuj}. Mohon konfirmasi penerimaan dan kondisi barang.\nTerima kasih, BIMA LOGISTICS.`},
'Tagihan':{to:'c',f:(o,r)=>`Yth. ${r.nama},\nTagihan pesanan ${kode(o)} (${o.asal} - ${o.tuj}, ${o.brg}) sebesar ${rp(o.biaya)}.\nMohon konfirmasi setelah pembayaran dilakukan.\nTerima kasih, BIMA LOGISTICS.`},
'Pesan bebas':{to:'*',free:1}};
const waRec=()=>{const[k,id]=$('#w-to').value.split(':'),x=k=='d'?gD(+id):gC(+id);return{...x,k}};
function waUpd(){const r=waRec(),os=S.ord.filter(o=>o.st!='Dibatalkan'&&(r.k=='d'?gT(o.trk).drv==r.id:o.cust==r.id));
$('#w-ord').innerHTML=os.length?os.map(o=>`<option value="${o.id}">${kode(o)}: ${o.asal} - ${o.tuj}</option>`).join(''):'<option value="">Tidak ada pesanan</option>';
$('#w-tpl').innerHTML=Object.keys(WAT).filter(n=>WAT[n].to==r.k||WAT[n].to=='*').map(n=>`<option>${n}</option>`).join('');waMsg()}
function waMsg(){const r=waRec(),o=S.ord.find(x=>x.id==$('#w-ord').value),t=WAT[$('#w-tpl').value];
$('#w-msg').value=!t?'':t.free?`Halo ${r.nama}, `:o?t.f(o,r):'';waLink()}
function waLink(){const r=waRec(),hp=normHp(r.hp),a=$('#w-link'),m=$('#w-msg').value.trim(),ok=validHp(hp)&&m;
if(!ok){a.removeAttribute('href');a.style.opacity='.5';$('#w-note').textContent=!validHp(hp)?'Nomor seluler penerima tidak valid.':'Pilih pesanan terkait atau isi pesan terlebih dahulu.';return}
a.href='https://wa.me/62'+hp.slice(1)+'?text='+encodeURIComponent(m);a.style.opacity='';$('#w-note').textContent='Tujuan: '+fmtHp(hp)}
function waGo(){if(!$('#w-link').getAttribute('href'))return false;const r=waRec();S.wa.push({t:new Date().toLocaleString('id-ID'),to:r.nama,hp:r.hp,tpl:$('#w-tpl').value,msg:$('#w-msg').value});$('#w-log').innerHTML=waLogHtml();return true}
function waLogHtml(){return tbl(['Waktu','Penerima','No. seluler','Jenis','Pesan','Aksi'],S.wa.map((x,i)=>[esc(x.t),esc(x.to),fmtHp(x.hp),esc(x.tpl),`<span style="white-space:normal;display:block;max-width:360px">${esc(x.msg.slice(0,120))}${x.msg.length>120?'...':''}</span>`,`<button class="btn s d" onclick="del('wa',${i})">Hapus</button>`]).reverse(),'Belum ada pesan yang dibuka di WhatsApp.')}
let EDT=null,CNF=null,BO=0;
const ab=(t,id)=>{const q=typeof id=='number'?id:`'${id}'`;return`<button class="btn s" onclick="edt('${t}',${q})">Edit</button> <button class="btn s d" onclick="del('${t}',${q})">Hapus</button>`};
const fld=(id,l,v,ty='text',ex='')=>`<label>${l}<input id="x-${id}" type="${ty}" value="${esc(v)}" ${ex}></label>`;
const sel=(id,l,os,v)=>`<label>${l}<select id="x-${id}">${os.map(([k,t])=>`<option value="${esc(k)}" ${k==v?'selected':''}>${esc(t)}</option>`).join('')}</select></label>`;
function ask(m,fn){CNF={m,fn};showModal()}
function cnfYes(){const f=CNF.fn;CNF=null;f();render()}
function cnfNo(){CNF=null;showModal()}
function edt(t,id){EDT={t,id};showModal()}
function edtClose(){EDT=null;showModal()}
function showModal(){const m=$('#modal');if(!m)return;
if(CNF){m.innerHTML=`<div class="ov"><div class="dlg" role="dialog" aria-modal="true"><h2>Konfirmasi hapus</h2><p>${esc(CNF.m)}</p><div class="full"><button class="btn" style="background:var(--bad);color:#fff" onclick="cnfYes()">Ya, hapus</button><button class="btn s" onclick="cnfNo()">Batal</button></div></div></div>`;return}
if(EDT){const f=editForm();m.innerHTML=`<div class="ov"><div class="dlg" role="dialog" aria-modal="true"><h2>${f.title}</h2><form onsubmit="saveEdit(event)">${f.html}<div class="full"><button class="btn">Simpan perubahan</button><button type="button" class="btn s" onclick="edtClose()">Batal</button></div></form></div></div>`;return}
m.innerHTML=''}
function editForm(){const{t,id}=EDT;let title='',h='';
if(t=='ord'){const o=S.ord.find(x=>x.id==id),can=o.st=='Dijadwalkan';title='Edit pesanan '+kode(o);
h=sel('cust','Pelanggan',S.cust.map(c=>[c.id,c.nama]),o.cust)+(can?acField('x-asal','Kota asal',o.asal)+acField('x-tuj','Kota tujuan',o.tuj)+sel('trk','Truk',S.trk.filter(k=>k.id==o.trk||(k.st=='Tersedia'&&gD(k.drv)&&gD(k.drv).st=='Aktif')).map(k=>[k.id,`${k.plat}, ${k.jenis} ${k.kap} kg, ${dN(k.drv)}`]),o.trk):'<p class="sub full">Rute dan truk hanya bisa diubah saat status Dijadwalkan.</p>')
+fld('brg','Jenis barang',o.brg,'text','required')+fld('berat','Berat (kg)',o.berat,'number','min="1" required')+fld('harga','Harga (Rp)',o.biaya,'number','min="1" required')+fld('tgl','Tanggal kirim',o.tgl,'date','required')+fld('almA','Alamat jemput',o.almA||'')+fld('almT','Alamat antar',o.almT||'')}
else if(t=='trk'){const k=gT(id);title='Edit truk '+k.plat;
h=fld('plat','Plat nomor',k.plat,'text','required')+sel('jenis','Jenis',Object.keys(PRE).map(j=>[j,j]),k.jenis)+fld('kap','Kapasitas (kg)',k.kap,'number','min="1" required')+fld('tarif','Tarif per km (Rp)',k.tarif,'number','min="1" required')
+sel('drv','Sopir',[[0,'Belum ada sopir'],...S.drv.filter(d=>d.id==k.drv||d.st=='Aktif').map(d=>[d.id,d.nama])],k.drv)+(k.st=='Bertugas'?'<p class="sub full">Truk sedang bertugas, sopir dan status tidak bisa diubah.</p>':sel('st','Status',[['Tersedia','Tersedia'],['Servis','Servis']],k.st))}
else if(t=='cust'){const c=gC(id);title='Edit pelanggan';h=fld('nama','Nama',c.nama,'text','required')+sel('kota','Kota',KOTA.map(k=>[k,k]),c.kota)+fld('hp','No. seluler',fmtHp(c.hp),'tel','required')}
else if(t=='drv'){const d=gD(id);title='Edit sopir '+d.nama;h=fld('nama','Nama',d.nama,'text','required')+fld('hp','No. seluler (dasar pelacakan)',fmtHp(d.hp),'tel','required')+sel('sim','Jenis SIM',[['B1 Umum','B1 Umum'],['B2 Umum','B2 Umum']],d.sim)+fld('exp','SIM berlaku sampai',d.exp,'date','required')+fld('alm','Alamat',d.alm==='-'?'':d.alm||'')+sel('st','Status',[['Aktif','Aktif'],['Cuti','Cuti']],d.st)}
else if(t=='exp'){const e=S.exp.find(x=>x.id==id);title='Edit pengeluaran';h=fld('tgl','Tanggal',e.tgl,'date','required')+sel('kat','Kategori',['BBM','Tol','Servis','Gaji sopir','Lainnya'].map(k=>[k,k]),e.kat)+sel('trk','Truk',S.trk.map(k=>[k.id,k.plat]),e.trk)+fld('jml','Jumlah (Rp)',e.jml,'number','min="1" required')+fld('ket','Keterangan',e.ket||'')}
else if(t=='rute'){const[a,u]=id.split('|');title='Edit harga rute '+a+' - '+u;h=fld('harga','Harga rute (Rp)',S.rute[id],'number','min="1" required')}
else if(t=='akun'){const a=S.akun.find(x=>x.uid==id);title='Edit user '+a.uid;h=fld('nama','Nama lengkap',a.nama,'text','required')+sel('role','Peran',['Admin','Operator','Sopir'].map(r=>[r,r]),a.role)+sel('drv','Data sopir (untuk peran Sopir)',S.drv.map(d=>[d.id,d.nama]),a.drv)+fld('pw','Kata sandi baru (kosongkan bila tidak diubah)','','password','minlength="6" autocomplete="new-password"')+sel('st','Status',[['Aktif','Aktif'],['Nonaktif','Nonaktif']],a.aktif?'Aktif':'Nonaktif')}
return{title,html:h}}
function saveEdit(e){e.preventDefault();const{t,id}=EDT,v=i=>$('#x-'+i).value,n=i=>+v(i);
if(t=='ord'){const o=S.ord.find(x=>x.id==id);
if(o.st=='Dijadwalkan'){const a=res(v('asal')),u=res(v('tuj'));if(!a||!u)return toast('Pilih kota dari daftar saran');if(a==u)return toast('Kota asal dan tujuan harus berbeda');
const nt=gT(n('trk'));if(n('berat')>nt.kap)return toast('Berat melebihi kapasitas truk '+nt.plat);
if(nt.id!=o.trk){freeTrk(o.trk);nt.st='Bertugas';o.trk=nt.id}o.asal=a;o.tuj=u;o.jarak=dist(a,u)}
else if(n('berat')>gT(o.trk).kap)return toast('Berat melebihi kapasitas truk');
Object.assign(o,{cust:n('cust'),brg:v('brg'),berat:n('berat'),biaya:n('harga'),tgl:v('tgl'),almA:v('almA'),almT:v('almT')})}
else if(t=='trk'){const k=gT(id);Object.assign(k,{plat:v('plat').toUpperCase(),jenis:v('jenis'),kap:n('kap'),tarif:n('tarif')});if(k.st!='Bertugas'){k.drv=n('drv');k.st=v('st')}}
else if(t=='cust'){const hp=normHp(v('hp'));if(!validHp(hp))return toast('Nomor seluler tidak valid. Contoh: 0812-1111-2222');Object.assign(gC(id),{nama:v('nama'),kota:v('kota'),hp})}
else if(t=='drv'){const d=gD(id),hp=normHp(v('hp')),k=S.trk.find(x=>x.drv==id);if(!validHp(hp))return toast('Nomor seluler tidak valid. Contoh: 0857-1000-2000');if(S.drv.some(x=>x.id!=id&&x.hp==hp))return toast('Nomor seluler sudah dipakai sopir lain');
if(v('st')=='Cuti'&&k&&k.st=='Bertugas')return toast('Sopir sedang bertugas');Object.assign(d,{nama:v('nama'),hp,sim:v('sim'),exp:v('exp'),alm:v('alm')||'-',st:v('st')})}
else if(t=='exp'){Object.assign(S.exp.find(x=>x.id==id),{tgl:v('tgl'),kat:v('kat'),trk:n('trk'),jml:n('jml'),ket:v('ket')})}
else if(t=='rute'){S.rute[id]=n('harga')}
else if(t=='akun'){const a=S.akun.find(x=>x.uid==id);if(a.uid==ME.uid&&(v('role')!=a.role||v('st')!='Aktif'))return toast('Peran dan status akun Anda sendiri tidak bisa diubah');
if(v('pw')&&v('pw').length<6)return toast('Kata sandi minimal 6 karakter');
Object.assign(a,{nama:v('nama'),role:v('role'),drv:v('role')=='Sopir'?n('drv'):0,aktif:v('st')=='Aktif'});if(v('pw'))a.pw=v('pw')}
EDT=null;toast('Perubahan disimpan');render()}
function del(t,id){
if(t=='ord'){const o=S.ord.find(x=>x.id==id);if(o.st=='Dalam perjalanan'||o.st=='Tiba di tujuan')return toast('Pesanan sedang berjalan. Selesaikan atau batalkan dulu.');
return ask(`Hapus pesanan ${kode(o)} beserta catatan biaya perjalanannya?`,()=>{if(o.st=='Dijadwalkan')freeTrk(o.trk);S.ord=S.ord.filter(x=>x.id!=id);S.trip=S.trip.filter(x=>x.oid!=id);toast('Pesanan dihapus')})}
if(t=='trk'){const k=gT(id),a=S.ord.filter(o=>o.trk==id).length,b=S.exp.filter(e=>e.trk==id).length;
if(a||b)return toast(`Truk ${k.plat} dipakai di ${a} pesanan dan ${b} pengeluaran, jadi tidak bisa dihapus. Ubah ke status Servis.`);
return ask(`Hapus truk ${k.plat}?`,()=>{S.trk=S.trk.filter(x=>x.id!=id);toast('Truk dihapus')})}
if(t=='cust'){const c=gC(id),a=S.ord.filter(o=>o.cust==id).length;if(a)return toast(`${c.nama} punya ${a} pesanan, jadi tidak bisa dihapus.`);
return ask(`Hapus pelanggan ${c.nama}?`,()=>{S.cust=S.cust.filter(x=>x.id!=id);toast('Pelanggan dihapus')})}
if(t=='drv'){const d=gD(id),k=S.trk.find(x=>x.drv==id);if(k&&k.st=='Bertugas')return toast('Sopir sedang bertugas.');
return ask(`Hapus sopir ${d.nama}? Penugasan truk dan akun login sopir ikut dilepas.`,()=>{S.trk.forEach(x=>{if(x.drv==id)x.drv=0});S.akun=S.akun.filter(a=>!(a.role=='Sopir'&&a.drv==id));S.drv=S.drv.filter(x=>x.id!=id);toast('Sopir dihapus')})}
if(t=='exp')return ask('Hapus pengeluaran ini?',()=>{S.exp=S.exp.filter(x=>x.id!=id);toast('Pengeluaran dihapus')});
if(t=='rute')return delRute(id);
if(t=='akun')return delAkun(id);
if(t=='wa')return ask('Hapus riwayat pesan ini?',()=>{S.wa.splice(id,1);toast('Riwayat dihapus')})}
document.addEventListener('keydown',e=>{if(e.key=='Escape'&&(EDT||CNF)){EDT=null;CNF=null;showModal()}});
let ME=null;
const isS=()=>ME&&ME.role=='Sopir',mine=o=>!isS()||gT(o.trk).drv==ME.drv;
const MENU={Admin:['dash','ord','trk','usr','gps','wa','biaya','fin','rep','akun'],Operator:['dash','ord','trk','usr','gps','wa','biaya','fin','rep'],Sopir:['dash','ord','gps']};
function loginView(){return `<div class="login"><div class="card"><div class="logo">BIMA<br><i>LOGISTICS</i></div><h1>Masuk</h1><p class="sub">Gunakan User ID yang diberikan admin.</p>
<form onsubmit="login(event)"><label class="full">User ID<input id="l-uid" autocomplete="username" required autofocus></label>
<label class="full">Kata sandi<input id="l-pw" type="password" autocomplete="current-password" required></label>
<p id="l-err" class="full" style="color:var(--bad);margin:0" role="alert"></p><button class="btn full">Masuk</button></form>
<p class="sub" style="margin:16px 0 0">Akun demo: admin / admin123, operator1 / operator123, budi / sopir123</p></div></div>`}
function login(e){e.preventDefault();const u=$('#l-uid').value.trim().toLowerCase(),a=S.akun.find(x=>x.uid==u&&x.pw==$('#l-pw').value);
if(!a){$('#l-err').textContent='User ID atau kata sandi salah.';return}
if(!a.aktif){$('#l-err').textContent='Akun ini dinonaktifkan. Hubungi admin.';return}
ME=a;cur='dash';render();toast('Selamat datang, '+a.nama)}
function logout(){ME=null;DONE=null;EDT=null;CNF=null;render()}
function cariHp(e){e.preventDefault();GQ=$('#g-hp').value;render()}
function addAkun(e){e.preventDefault();const uid=$('#a-uid').value.trim().toLowerCase(),role=$('#a-role').value;
if(S.akun.some(a=>a.uid==uid))return toast('User ID sudah dipakai');
S.akun.push({uid,nama:$('#a-nama').value,role,pw:$('#a-pw').value,drv:role=='Sopir'?+$('#a-drv').value:0,aktif:true});toast('User ID '+uid+' dibuat');render()}
function togAkun(u){const a=S.akun.find(x=>x.uid==u);a.aktif=!a.aktif;render()}
function delAkun(u){ask('Hapus user '+u+'?',()=>{S.akun=S.akun.filter(x=>x.uid!=u);toast('User dihapus')})}
const NAV=[['dash','Dashboard'],['ord','Pesanan'],['trk','Armada'],['usr','Pengguna'],['gps','Pelacakan'],['wa','WhatsApp'],['biaya','Biaya Perjalanan'],['fin','Keuangan'],['rep','Laporan'],['akun','Akun & User ID']];
let cur='dash';
function go(v){cur=v;render();window.scrollTo(0,0)}
function render(){document.body.classList.toggle('out',!ME);
if(!ME){$('#main').innerHTML=loginView();$('#modal').innerHTML='';return}
if(!MENU[ME.role].includes(cur))cur='dash';
$('#nav').innerHTML=NAV.filter(([k])=>MENU[ME.role].includes(k)).map(([k,t])=>`<button class="${k==cur?'on':''}" onclick="go('${k}')">${t}</button>`).join('')+'<button onclick="logout()">Keluar</button>';
$('#main').innerHTML=`<div class="who">${esc(ME.nama)} <span class="bd">${ME.role}</span> @${esc(ME.uid)}</div>`+V[cur]();
if(cur=='ord')fillTrk();
if(cur=='biaya'){if(BO){$('#b-ord').value=BO;BO=0}loadTrip()}
if(cur=='wa')waUpd();
if(isS()&&cur=='dash')document.querySelectorAll('.kpi.g,.kpi:not(.a):not(.b)').forEach(e=>e.remove());showModal()}
setInterval(()=>{let ch=false,arr=false;S.ord.forEach(o=>{if(o.st=='Dalam perjalanan'){o.prog=Math.min(1,o.prog+.02);ch=true;if(o.prog>=1){o.st='Tiba di tujuan';arr=true;toast(kode(o)+' tiba, konfirmasi penyelesaian')}}});
if(ME&&ch&&(cur=='gps'||cur=='dash')&&!(document.activeElement&&document.activeElement.id=='g-hp')&&!EDT&&!CNF)render();
if(ME&&arr&&cur=='ord'&&DONE==null&&!EDT&&!CNF){const ids=['o-cust','o-asal','o-tuj','o-brg','o-berat','o-tgl'],v=ids.map(i=>$('#'+i).value);render();ids.forEach((i,k)=>$('#'+i).value=v[k]);fillTrk()}},2000);
render();
</script></body></html>

