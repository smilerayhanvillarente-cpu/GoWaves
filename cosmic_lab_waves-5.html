<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Cosmic Lab: Waves</title>
<link rel="preconnect" href="https://fonts.googleapis.com"><link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,600&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--ink:#04101a;--deep:#08202e;--line:#16384a;--tx:#dff3f6;--mut:#86a9b4;--aq:#4fd8cf;--am:#ffb454;--pk:#f472b6;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-padding-top:env(safe-area-inset-top,0px);height:100%;background:#04101a}
*{box-sizing:border-box}
body{margin:0;height:100%;display:flex;flex-direction:column;background:#04101a;color:var(--tx);font:15px/1.5 "IBM Plex Sans",system-ui,sans-serif;overflow:hidden}
h1,h2,h3{font-family:Fraunces,Georgia,serif;font-weight:600;margin:0}
#view{position:relative;flex:0 0 44%;min-height:230px}
#c{width:100%;height:100%;display:block;touch-action:none;cursor:grab}
.ov{position:absolute;pointer-events:none}
#title{left:14px;top:12px;font-size:22px}#title small{display:block;font:12px "IBM Plex Sans";color:var(--mut)}
#btns{right:10px;top:10px;display:flex;gap:6px;pointer-events:auto}
#hint{left:14px;bottom:8px;font-size:11px;color:var(--mut)}
button{font:inherit;color:inherit;cursor:pointer}
.b{background:rgba(8,32,46,.8);border:1px solid var(--line);border-radius:8px;padding:5px 10px;font-size:12px}
.b.on{border-color:var(--aq);color:var(--aq)}
#panel{flex:1;overflow:auto;background:var(--deep);border-top:1px solid var(--line)}
#tabs{display:flex;gap:4px;padding:8px 10px;position:sticky;top:0;background:var(--deep);z-index:2;overflow-x:auto;border-bottom:1px solid var(--line)}
.tab{flex:none;background:none;border:1px solid transparent;border-radius:8px;padding:7px 12px;color:var(--mut);font-weight:500}
.tab.on{border-color:var(--aq);color:var(--aq);background:rgba(79,216,207,.08)}
.sec{padding:14px 16px}
.row{margin-bottom:12px}.row div{display:flex;justify-content:space-between;font-size:13px}.row b{color:var(--aq);font-weight:600;font-variant-numeric:tabular-nums}
input[type=range]{width:100%;accent-color:#4fd8cf;margin:4px 0 0}
.seg{display:flex;gap:6px;margin-bottom:14px;flex-wrap:wrap}
#read{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin:6px 0 12px}
#read div{border:1px solid var(--line);border-radius:10px;padding:8px 10px;background:rgba(4,16,26,.5)}
#read span{display:block;font-size:11px;color:var(--mut)}#read b{font-size:16px;font-variant-numeric:tabular-nums}
.eq{font-family:Fraunces,serif;font-size:18px;text-align:center;padding:10px;border-radius:10px;background:rgba(79,216,207,.07);margin-bottom:12px}
#note{color:#b9d6dd;font-size:14px}#note b{color:var(--tx)}
details{border-bottom:1px solid var(--line);padding:10px 0}summary{cursor:pointer;font-weight:600}details p,details li{color:#b9d6dd;font-size:14px;margin:8px 0 0}details ul{padding-left:18px;margin:0}
.q{margin:10px 0 0}.q button{display:block;width:100%;text-align:left;margin-top:6px;padding:9px 12px;border-radius:10px;border:1px solid var(--line);background:rgba(4,16,26,.5)}
.q button.ok{border-color:#4fd8cf;background:rgba(79,216,207,.15)}.q button.no{border-color:#ff6b6b}
.ex{font-size:13px;color:var(--mut);margin-top:6px}
.chip{border-color:var(--line);font-size:12px;padding:5px 9px}
@media(min-width:900px){body{flex-direction:row}#view{flex:1}#panel{flex:0 0 440px;border-top:0;border-left:1px solid var(--line)}}
</style></head><body>
<div id="view"><canvas id="c"></canvas>
<div id="title" class="ov"></div>
<div id="btns" class="ov"><button class="b" id="pz">Pause</button><button class="b" id="sl">Slow motion</button></div>
<div id="hint" class="ov">Drag to orbit. Pinch or scroll to zoom.</div></div>
<div id="panel"><div id="tabs"></div>
<div id="lab" class="sec"><div id="ctrl"></div><div id="read"></div><div id="note"></div></div>
<div id="learn" class="sec" hidden>
<h2 style="margin-bottom:6px">Wave field guide</h2>
<details open><summary>What is a wave?</summary><p>A wave is a disturbance that carries energy from place to place without carrying matter along. A cork on the sea bobs in place while the wave moves on.</p></details>
<details><summary>Mechanical, electromagnetic, matter</summary><ul><li><b>Mechanical</b> waves (sound, water, seismic, strings) need a medium to push on.</li><li><b>Electromagnetic</b> waves are linked electric and magnetic fields. They cross vacuum at c = 3.00×10⁸ m/s.</li><li><b>Matter waves</b>: electrons and atoms also show wave behaviour.</li></ul></details>
<details><summary>Transverse, longitudinal, surface</summary><ul><li><b>Transverse</b>: the medium moves at right angles to travel (strings, light, S-waves). Crests and troughs.</li><li><b>Longitudinal</b>: the medium moves along the travel direction (sound, P-waves). Compressions and rarefactions.</li><li><b>Surface</b>: a mix. Water particles trace circles or ellipses, as the Ocean tab shows.</li></ul></details>
<details><summary>The quantities</summary><ul><li>Amplitude: the peak displacement. A bigger amplitude carries more energy.</li><li>Wavelength λ: the distance from crest to crest.</li><li>Period: the time for one full cycle. Frequency: how many cycles happen each second.</li><li>Wave speed: how fast the pattern travels. The medium sets the speed; the source sets the frequency.</li></ul></details>
<details><summary>What waves do</summary><ul><li><b>Reflection</b>: angle in = angle out. A fixed end flips the pulse.</li><li><b>Refraction</b>: speed changes at a boundary, so the wave bends.</li><li><b>Diffraction</b>: waves spread around edges and through gaps, most when the gap is near λ.</li><li><b>Superposition</b>: overlapping waves add. If the two paths differ by a whole number of wavelengths the waves reinforce; by an odd number of half-wavelengths they cancel.</li><li><b>Standing waves</b>: two equal waves travelling opposite ways make nodes and antinodes.</li><li><b>Doppler effect</b>: a source moving toward you raises the observed frequency.</li><li><b>Polarization</b>: only transverse waves can be polarized.</li></ul></details>
<details><summary>Sound</summary><p>Longitudinal, about 343 m/s in air at 20 °C, 1480 m/s in water, 5960 m/s in steel. Pitch follows frequency, loudness follows amplitude. Humans hear roughly 20 Hz to 20 kHz.</p></details>
<details><summary>Light and the spectrum</summary><p>Visible light spans about 380 nm (violet) to 750 nm (red). In a material of refractive index n, light slows down and its wavelength shrinks, but its frequency stays fixed. Shorter wavelengths carry more energy per photon. That is why X-rays and gamma rays ionize atoms. Use the Light tab to explore every band.</p></details>
<details><summary>Earthquake waves</summary><ul><li><b>P-waves</b> are longitudinal and fast. They travel through solids and liquids.</li><li><b>S-waves</b> are transverse and slower. They cannot travel through liquid, which is how scientists found that the outer core is liquid.</li><li>A seismograph records the P-wave first, then the S-wave. The longer the gap, the farther away the quake.</li></ul></details>
<h2 style="margin:18px 0 4px">Knowledge check</h2><div id="quiz"></div></div></div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script>
const $=s=>document.querySelector(s),cl=(v,a,b)=>Math.max(a,Math.min(b,v)),PI2=Math.PI*2;
const cv=$('#c'),R=new THREE.WebGLRenderer({canvas:cv,antialias:true});R.setPixelRatio(Math.min(devicePixelRatio,2));
const sc=new THREE.Scene();sc.background=new THREE.Color(0x04101a);sc.fog=new THREE.Fog(0x04101a,40,90);
const cam=new THREE.PerspectiveCamera(50,1,.1,200);
sc.add(new THREE.HemisphereLight(0xaee6ff,0x0a2030,.9));const sun=new THREE.DirectionalLight(0xfff1d6,1.3);sun.position.set(-10,14,8);sc.add(sun);
function size(){const v=$('#view');R.setSize(v.clientWidth,v.clientHeight,false);cam.aspect=v.clientWidth/v.clientHeight;cam.updateProjectionMatrix()}
new ResizeObserver(size).observe($('#view'));
let c3={th:.5,ph:1.1,r:26},ptr=new Map(),pd=1,paused=false,slow=false,t=0,cur=null,fr=0;
const pinch=()=>{const a=[...ptr.values()];return a.length<2?1:Math.hypot(a[0][0]-a[1][0],a[0][1]-a[1][1])};
cv.onpointerdown=e=>{cv.setPointerCapture(e.pointerId);ptr.set(e.pointerId,[e.clientX,e.clientY]);pd=pinch()};
cv.onpointermove=e=>{if(!ptr.has(e.pointerId))return;const o=ptr.get(e.pointerId);ptr.set(e.pointerId,[e.clientX,e.clientY]);
 if(ptr.size==1){c3.th-=(e.clientX-o[0])*.007;c3.ph=cl(c3.ph-(e.clientY-o[1])*.007,.2,1.5)}else{const d=pinch();c3.r=cl(c3.r*pd/d,9,50);pd=d}};
cv.onpointerup=cv.onpointercancel=e=>ptr.delete(e.pointerId);
cv.addEventListener('wheel',e=>{e.preventDefault();c3.r=cl(c3.r*(1+e.deltaY*.001),9,50)},{passive:false});
$('#pz').onclick=e=>{paused=!paused;e.target.textContent=paused?'Play':'Pause';e.target.classList.toggle('on',paused)};
$('#sl').onclick=e=>{slow=!slow;e.target.classList.toggle('on',slow)};
const D=new THREE.Object3D(),mk=(c,e)=>new THREE.MeshStandardMaterial({color:c,emissive:c,emissiveIntensity:e||.6,roughness:.4});
const grid=(y)=>{const g=new THREE.GridHelper(60,60,0x15485a,0x0b2633);g.position.y=y;return g};
function si(x,u){for(const[a,s]of [[1e12,'T'],[1e9,'G'],[1e6,'M'],[1e3,'k'],[1,''],[1e-3,'m'],[1e-6,'µ'],[1e-9,'n'],[1e-12,'p'],[1e-15,'f']])if(x>=a)return (x/a).toPrecision(3)+' '+s+u;return x.toExponential(1)+' '+u}
const P={};const defs={};

/* ---------- 1. Medium ---------- */
defs.med={name:'Medium',sub:'Particles in a 3D medium',sl:[['A','Amplitude (m)',.1,1.5,.01,.6],['f','Frequency (Hz)',.4,4,.01,1.2],['T','Stiffness',20,100,1,50],['mu','Density',.05,.4,.01,.1]],
 seg:['Transverse','Longitudinal'],cam:[.55,1.15,24],eq:'v = fλ = √(stiffness ÷ density)',
 note:()=>P.med.seg?'<b>Longitudinal.</b> Each particle shuttles along the travel direction. Orange regions are compressions (high density), blue are rarefactions. The wave pattern moves right; the particles only jiggle.':'<b>Transverse.</b> Each particle moves up and down while the pattern travels right. The amber row shows the wave profile. Stiffer or lighter medium: faster wave. Same frequency, faster wave: longer λ.',
 build(){const g=new THREE.Group(),NX=64,N=NX*25;this.base=[];this.col=new THREE.Color();
  this.im=new THREE.InstancedMesh(new THREE.SphereGeometry(.1,12,10),new THREE.MeshStandardMaterial({roughness:.35,metalness:.3}),N);
  let i=0;for(let a=0;a<NX;a++)for(let b=0;b<5;b++)for(let c=0;c<5;c++){this.base.push([(a-NX/2)*.5,(b-2)*.5,(c-2)*.5,b==2&&c==2]);this.im.setColorAt(i++,this.col.set(0x2b8ea0))}
  this.br=new THREE.Mesh(new THREE.BoxGeometry(1,.05,.05),mk(0xffffff,1));this.br.position.y=2.6;
  g.add(this.im,this.br,grid(-2.4));return g},
 upd(t){const p=P.med,L=p.seg,v=Math.sqrt(p.T/p.mu),lam=v/p.f,k=PI2/lam,w=PI2*p.f,amp=L?Math.min(p.A*.3,.6/k):p.A,col=this.col;let i=0;
  const cool=new THREE.Color(0x2a6bff),hot=new THREE.Color(0xff7a3d);
  for(const[x,y,z,h]of this.base){const ph=k*x-w*t,s=amp*Math.sin(ph);
   L?D.position.set(x+s,y,z):D.position.set(x,y+s,z);D.scale.setScalar(h?1.5:1);D.updateMatrix();this.im.setMatrixAt(i,D.matrix);
   L?col.copy(cool).lerp(hot,(1-Math.cos(ph))/2):col.set(h?0xffb454:0x2b8ea0);this.im.setColorAt(i++,col)}
  this.im.instanceMatrix.needsUpdate=this.im.instanceColor.needsUpdate=true;this.br.scale.x=Math.min(lam,30)},
 read(){const p=P.med,v=Math.sqrt(p.T/p.mu);return [['Wave speed v',v.toFixed(1)+' m/s'],['Wavelength λ',(v/p.f).toFixed(2)+' m'],['Period T',(1/p.f).toFixed(2)+' s'],['Relative energy',(p.A*p.A).toFixed(2)]]}};

/* ---------- 2. Ocean ---------- */
const VS=`uniform float uT;uniform vec4 uW[3];uniform vec2 uA[3];varying vec3 vN;varying vec3 vP;varying float vH;
void main(){vec3 p=position,n=vec3(0.,1.,0.),d=vec3(0.);
for(int i=0;i<3;i++){vec4 w=uW[i];float ph=w.z*dot(w.xy,position.xz)-w.w*uT,c=cos(ph),s=sin(ph),a=uA[i].x,q=uA[i].y;
d+=vec3(w.x*q*a*c,a*s,w.y*q*a*c);n.xz-=w.xy*w.z*a*c;n.y-=q*w.z*a*s;}
p+=d;vH=d.y;vN=normalize(n);vP=p;gl_Position=projectionMatrix*modelViewMatrix*vec4(p,1.);}`;
const FS=`uniform float uF;varying vec3 vN;varying vec3 vP;varying float vH;
void main(){vec3 N=normalize(vN),V=normalize(cameraPosition-vP),L=normalize(vec3(-.5,.8,.4));
float fr=pow(1.-max(dot(N,V),0.),4.);vec3 col=mix(vec3(.01,.09,.16),vec3(.05,.45,.52),clamp(vH/uF*.5+.45,0.,1.));
col*=.4+.6*max(dot(N,L),0.);col=mix(col,vec3(.35,.62,.82),fr*.65);
col+=pow(max(dot(reflect(-L,N),V),0.),80.)*vec3(1.,.95,.8)+smoothstep(.72,1.,vH/uF)*.35;
col=mix(col,vec3(.016,.063,.102),smoothstep(16.,26.,length(vP.xz)));gl_FragColor=vec4(col,1.);}`;
function oceanWaves(){const o=P.oc,k=PI2/o.L,th=o.th*Math.PI/180,ws=[[th,k,o.A],[th+.55,k*1.8,o.A*.22],[th-.7,k*2.9,o.A*.1]];
 const S=ws.reduce((s,w)=>s+w[1]*w[2],0),q=Math.min(o.Q,.9/S);return ws.map(w=>({dx:Math.cos(w[0]),dz:Math.sin(w[0]),k:w[1],w:Math.sqrt(9.81*w[1]),a:w[2],q}))}
defs.oc={name:'Ocean',sub:'Real-scale deep-water waves',sl:[['A','Amplitude (m)',.1,1.2,.01,.5],['L','Wavelength (m)',4,22,.1,12],['Q','Crest sharpness',0,1,.01,.7],['th','Direction (°)',0,360,1,20]],
 cam:[.35,1.0,26],eq:'v = √(gλ / 2π)   (deep water)',
 note:()=>'<b>Follow an orange buoy.</b> It does not travel with the wave; it circles on the ring, up at the crest and back at the trough. Water particles move in orbits, and the energy moves on. Longer waves travel faster, so wavelength and speed are tied together here. Push crest sharpness up and crests peak while troughs flatten (Gerstner waves). Real waves break when height/λ passes about 1/7.',
 build(){const g=new THREE.Group();this.u={uT:{value:0},uF:{value:1},uW:{value:[0,1,2].map(()=>new THREE.Vector4())},uA:{value:[0,1,2].map(()=>new THREE.Vector2())}};
  const geo=new THREE.PlaneGeometry(56,56,200,200);geo.rotateX(-Math.PI/2);
  g.add(new THREE.Mesh(geo,new THREE.ShaderMaterial({uniforms:this.u,vertexShader:VS,fragmentShader:FS})));
  this.bu=[[-9,4],[-3,4],[4,4]].map(([x,z])=>{const m=new THREE.Mesh(new THREE.SphereGeometry(.38,20,14),mk(0xffb454,.7)),r=new THREE.Group(),pts=[];
   for(let i=0;i<=64;i++)pts.push(new THREE.Vector3(Math.cos(i/64*PI2),Math.sin(i/64*PI2),0));
   r.add(new THREE.Line(new THREE.BufferGeometry().setFromPoints(pts),new THREE.LineBasicMaterial({color:0xffb454,transparent:true,opacity:.6})));r.position.set(x,0,z);g.add(m,r);return{m,r,x,z}});return g},
 upd(t){const ws=oceanWaves(),o=P.oc;ws.forEach((w,i)=>{this.u.uW.value[i].set(w.dx,w.dz,w.k,w.w);this.u.uA.value[i].set(w.a,w.q)});this.u.uT.value=t;this.u.uF.value=o.A*1.35;
  const th=o.th*Math.PI/180;for(const b of this.bu){let x=b.x,y=0,z=b.z;for(const w of ws){const ph=w.k*(w.dx*b.x+w.dz*b.z)-w.w*t;x+=w.dx*w.q*w.a*Math.cos(ph);z+=w.dz*w.q*w.a*Math.cos(ph);y+=w.a*Math.sin(ph)}
   b.m.position.set(x,y,z);b.r.rotation.y=-th;b.r.scale.set(o.A*ws[0].q,o.A,1)}},
 read(){const o=P.oc,c=Math.sqrt(9.81*o.L/PI2);return [['Wave speed c',c.toFixed(2)+' m/s'],['Frequency f',(c/o.L).toFixed(3)+' Hz'],['Period T',(o.L/c).toFixed(2)+' s'],['Steepness',(2*o.A/o.L).toFixed(3)+(2*o.A/o.L>.143?' (breaking)':'')],['Orbit radius',o.A.toFixed(2)+' m'],['Relative energy',(o.A*o.A).toFixed(2)]]}};

/* ---------- 3. Interference ---------- */
defs.itf={name:'Interference',sub:'Two sources, one surface',sl:[['L','Wavelength (m)',1.5,6,.05,3],['A','Amplitude',.2,1,.01,.6],['d','Source spacing (m)',1,14,.1,6],['ph','Phase offset (rad)',0,3.14,.01,0],['px','Probe position (m)',-11,11,.1,3]],
 seg:['Two sources','One source'],cam:[0,.95,30],eq:'Path difference = mλ → bright     (m + ½)λ → dark',
 note:()=>'<b>Move the probe.</b> The amber marker sits where the two waves meet. If one wave travels a whole number of wavelengths farther than the other, crests meet crests and the water rocks hard. If the gap is a half-wavelength odd number, a crest meets a trough and the water stays still. Those still lines (nodal lines) fan out from between the sources. Widen the spacing or shrink λ and they crowd closer.',
 build(){const g=new THREE.Group(),geo=new THREE.PlaneGeometry(30,30,140,140);geo.rotateX(-Math.PI/2);
  geo.setAttribute('color',new THREE.BufferAttribute(new Float32Array(geo.attributes.position.count*3),3));this.geo=geo;
  g.add(new THREE.Mesh(geo,new THREE.MeshPhongMaterial({vertexColors:true,shininess:90,specular:0x88ccdd})));
  this.src=[0,1].map(()=>{const m=new THREE.Mesh(new THREE.SphereGeometry(.35,16,12),mk(0xf472b6,1));g.add(m);return m});
  this.pr=new THREE.Mesh(new THREE.SphereGeometry(.4,16,12),mk(0xffb454,1));g.add(this.pr);return g},
 srcs(){const p=P.itf;return p.seg?[[0,-9]]:[[-p.d/2,-9],[p.d/2,-9]]},
 upd(t){const p=P.itf,k=PI2/p.L,w=k*3,S=this.srcs(),pa=this.geo.attributes.position,ca=this.geo.attributes.color;
  const hAt=(x,z)=>{let h=0;S.forEach((s,i)=>{h+=p.A*Math.cos(k*Math.hypot(x-s[0],z-s[1])-w*t+(i?p.ph:0))/Math.sqrt(1+.3*Math.hypot(x-s[0],z-s[1]))});return h};
  for(let i=0;i<pa.count;i++){const h=hAt(pa.getX(i),pa.getZ(i)),u=cl(.5+.5*h/(p.A*1.3),0,1);pa.setY(i,h);ca.setXYZ(i,.02+.5*u,.19+.75*u*u+.1*u,.29+.7*u)}
  pa.needsUpdate=ca.needsUpdate=true;this.geo.computeVertexNormals();
  this.src.forEach((m,i)=>{m.visible=!!S[i];if(S[i])m.position.set(S[i][0],.4,S[i][1])});this.pr.position.set(p.px,hAt(p.px,8)+.2,8)},
 read(){const p=P.itf,S=this.srcs();let m='-',v='One source: no interference';
  if(S.length>1){const r=S.map(s=>Math.hypot(p.px-s[0],8-s[1]));const x=(r[0]-r[1])/p.L-p.ph/PI2,f=Math.abs(x-Math.round(x));m=x.toFixed(2)+' λ';v=f<.12?'Constructive':f>.38?'Destructive':'Partial'}
  return [['Wavelength λ',p.L.toFixed(2)+' m'],['Frequency f',(3/p.L).toFixed(2)+' Hz'],['Path diff at probe',m],['Probe result',v]]}};

/* ---------- 4. Light ---------- */
const bands=[['Radio',3e5,3e8,'Broadcast, Wi-Fi bands, radar'],['Microwave',3e8,3e11,'Ovens, satellites, 5G'],['Infrared',3e11,4e14,'Thermal cameras, remotes'],['Visible',4e14,7.9e14,'What eyes detect'],['Ultraviolet',7.9e14,3e16,'Sterilizing, tanning, forensics'],['X-ray',3e16,3e19,'Medical imaging, crystallography'],['Gamma',3e19,3e21,'Nuclear decay, cancer therapy']];
function wl(w){let r=0,g=0,b=0;if(w<440){r=(440-w)/60;b=1}else if(w<490){g=(w-440)/50;b=1}else if(w<510){g=1;b=(510-w)/20}else if(w<580){r=(w-510)/70;g=1}else if(w<645){r=1;g=(645-w)/65}else r=1;return new THREE.Color(r,g,b)}
defs.em={name:'Light',sub:'Electromagnetic waves',sl:[['A','Amplitude (field strength)',.2,1.5,.01,.7],['s','Frequency inside band',0,1,.01,.5],['n','Refractive index n',1,2.4,.01,1]],
 cam:[.9,1.15,25],eq:'c = fλ     E = hf     v = c / n',chips:true,
 note:()=>'<b>Pink</b> is the electric field, <b>amber</b> the magnetic field. They oscillate at right angles to each other and to the travel direction, and they sustain each other, so no medium is needed. Raise n (glass is about 1.5, diamond 2.4): the wave slows and λ shrinks, but the frequency, and so the colour, does not change. The pictured number of cycles is schematic; real wavelengths span 18 orders of magnitude.',
 build(){const g=new THREE.Group(),N=240,NS=160;this.NS=NS;
  const line=(c,n)=>{const l=new THREE.Line(new THREE.BufferGeometry().setAttribute('position',new THREE.BufferAttribute(new Float32Array(n*3),3)),new THREE.LineBasicMaterial({color:c}));l.frustumCulled=false;return l};
  const seg=(c)=>{const l=new THREE.LineSegments(new THREE.BufferGeometry().setAttribute('position',new THREE.BufferAttribute(new Float32Array(NS*6),3)),new THREE.LineBasicMaterial({color:c,transparent:true,opacity:.45}));l.frustumCulled=false;return l};
  this.eL=line(0xf472b6,N);this.bL=line(0xffb454,N);this.eS=seg(0xf472b6);this.bS=seg(0xffb454);
  const ax=new THREE.Mesh(new THREE.CylinderGeometry(.03,.03,32,6),mk(0xdff3f6,.3));ax.rotation.z=Math.PI/2;
  const ar=new THREE.Mesh(new THREE.ConeGeometry(.25,.7,12),mk(0xdff3f6,.5));ar.rotation.z=-Math.PI/2;ar.position.x=16.3;
  g.add(this.eL,this.bL,this.eS,this.bS,ax,ar,grid(-3));return g},
 f(){const p=P.em,b=bands[p.b||3];return b[1]*Math.pow(b[2]/b[1],p.s)},
 upd(t){const p=P.em,f=this.f(),n=p.n,cyc=(1+7*(Math.log10(f)-5)/16)*n,k=cyc*PI2/30,w=2.2*k/n*2.2/2.2;
  const e=this.eL.geometry.attributes.position,b=this.bL.geometry.attributes.position,es=this.eS.geometry.attributes.position,bs=this.bS.geometry.attributes.position,N=e.count;
  for(let i=0;i<N;i++){const x=-15+30*i/(N-1),s=Math.sin(k*x-w*t)*p.A*2;e.setXYZ(i,x,s,0);b.setXYZ(i,x,0,s)}
  for(let i=0;i<this.NS;i++){const x=-15+30*i/(this.NS-1),s=Math.sin(k*x-w*t)*p.A*2;es.setXYZ(2*i,x,0,0);es.setXYZ(2*i+1,x,s,0);bs.setXYZ(2*i,x,0,0);bs.setXYZ(2*i+1,x,0,s)}
  e.needsUpdate=b.needsUpdate=es.needsUpdate=bs.needsUpdate=true;
  const ec=(p.b||3)==3?wl(299792458/f*1e9):new THREE.Color(0xf472b6);this.eL.material.color.copy(ec);this.eS.material.color.copy(ec)},
 read(){const p=P.em,f=this.f(),l=299792458/f,E=6.626e-34*f/1.602e-19,b=bands[p.b||3];return [['Frequency f',si(f,'Hz')],['Wavelength in vacuum',si(l,'m')],['Wavelength in medium',si(l/p.n,'m')],['Speed in medium',(299792458/p.n/1e8).toFixed(2)+'×10⁸ m/s'],['Photon energy',E<1e3?E.toPrecision(3)+' eV':si(E,'eV')],['Used for',b[3]]]}};

/* ---------- 5. Earthquake ---------- */
const ER=10,RC=5.5,VC=.7,SV=.55,NR=240,TR=5,KM=637;let shk=0,dn=null;
const dot2=(a,b)=>a[0]*b[0]+a[1]*b[1];
function hit(p,d,r){const b=dot2(p,d),c=dot2(p,p)-r*r,q=b*b-c;if(q<0)return null;const s=Math.sqrt(q);return[-b-s,-b+s]}
function refr(d,N,e){const ci=-dot2(d,N),s2=e*Math.sqrt(Math.max(0,1-ci*ci)),ct=Math.sqrt(Math.max(0,1-s2*s2));return[e*d[0]+(e*ci-ct)*N[0],e*d[1]+(e*ci-ct)*N[1]]}
function trace(F,d,S){const hc=hit(F,d,RC),ex=hit(F,d,ER)[1],ent=hc&&hc[0]>1e-6?hc[0]:null,pts=[F],cum=[0],v=S?SV:1;
 const add=(q,tt)=>{pts.push(q);cum.push(cum[cum.length-1]+tt)};
 if(ent!==null&&ent<ex){const q=[F[0]+d[0]*ent,F[1]+d[1]*ent];add(q,ent/v);
  if(S)return{pts,cum,blocked:true,end:q};
  const d2=refr(d,[q[0]/RC,q[1]/RC],VC),h=hit(q,d2,RC)[1],q2=[q[0]+d2[0]*h,q[1]+d2[1]*h];add(q2,h/VC);
  const d3=refr(d2,[-q2[0]/RC,-q2[1]/RC],1/VC),h3=hit(q2,d3,ER)[1],q3=[q2[0]+d3[0]*h3,q2[1]+d3[1]*h3];add(q3,h3);return{pts,cum,end:q3}}
 const q=[F[0]+d[0]*ex,F[1]+d[1]*ex];add(q,ex/v);return{pts,cum,end:q}}
function posAt(r,T){const c=r.cum;if(T<0||T>c[c.length-1])return null;let i=1;while(c[i]<T)i++;const f=(T-c[i-1])/(c[i]-c[i-1]||1),a=r.pts[i-1],b=r.pts[i];return[a[0]+(b[0]-a[0])*f,a[1]+(b[1]-a[1])*f]}
const vib=p=>{try{navigator.vibrate&&navigator.vibrate(p)}catch(e){}};
const glow=()=>{const c=document.createElement('canvas');c.width=c.height=64;const g=c.getContext('2d'),gr=g.createRadialGradient(32,32,0,32,32,32);gr.addColorStop(0,'#fff');gr.addColorStop(.35,'rgba(255,255,255,.6)');gr.addColorStop(1,'rgba(255,255,255,0)');g.fillStyle=gr;g.fillRect(0,0,64,64);return new THREE.CanvasTexture(c)};
const mkPts=(n,size,tex)=>{const g=new THREE.BufferGeometry();g.setAttribute('position',new THREE.BufferAttribute(new Float32Array(n*3),3));g.setAttribute('color',new THREE.BufferAttribute(new Float32Array(n*3),3));const p=new THREE.Points(g,new THREE.PointsMaterial({size,map:tex,vertexColors:true,transparent:true,blending:THREE.AdditiveBlending,depthWrite:false,depthTest:false}));p.frustumCulled=false;p.renderOrder=5;return p};
defs.eq={name:'Earthquake',sub:'Tap inside the Earth to set one off',hint:'Tap inside the Earth to start a quake. Drag to orbit.',
 sl:[['mag','Magnitude',.3,1.5,.01,.8],['sa','Station position (°)',0,360,1,270]],seg:['P and S waves','P waves only','S waves only'],cam:[.45,1.3,25],
 note:()=>'<b>Tap anywhere inside the Earth</b> to set off a quake. <b style="color:#ffb454">P-waves</b> (orange) are squeezes, like sound: fast, and they cross solids and liquids. <b style="color:#f472b6">S-waves</b> (pink) shake sideways: slower, and they cannot cross liquid, so they stop at the outer core. P-waves bend as they enter the core, which leaves a gap on the far side where no direct P-wave lands (the shadow zone). Move the station and watch the seismograph: the longer the wait between P and S, the farther away the quake. This is a simplified model with straight paths inside the mantle.',
 build(){const g=new THREE.Group(),tex=glow(),clip=new THREE.Plane(new THREE.Vector3(0,0,-1),0);R.localClippingEnabled=true;
  const ring=(a,b,c,o)=>g.add(new THREE.Mesh(new THREE.RingGeometry(a,b,96),new THREE.MeshBasicMaterial({color:c,transparent:true,opacity:o,side:THREE.DoubleSide})));
  ring(9.6,ER,0x4a3329,1);ring(RC,9.6,0x8a3626,.78);ring(2,RC,0xff9d3a,.62);g.add(new THREE.Mesh(new THREE.CircleGeometry(2,48),new THREE.MeshBasicMaterial({color:0xfff0c8})));
  [[ER,0x5a382c,.3],[RC,0xff9d3a,.3],[2,0xfff0c8,.9]].forEach(([r,c,o])=>g.add(new THREE.Mesh(new THREE.SphereGeometry(r,48,32),new THREE.MeshStandardMaterial({color:c,emissive:c,emissiveIntensity:.25,transparent:true,opacity:o,side:THREE.DoubleSide,clippingPlanes:[clip]}))));
  const lab=(s,x,y)=>{const c=document.createElement('canvas');c.width=256;c.height=64;const q=c.getContext('2d');q.font='600 30px IBM Plex Sans,sans-serif';q.fillStyle='#fff';q.textAlign='center';q.fillText(s,128,42);const sp=new THREE.Sprite(new THREE.SpriteMaterial({map:new THREE.CanvasTexture(c),transparent:true,opacity:.85,depthTest:false}));sp.scale.set(3.2,.8,1);sp.position.set(x,y,.1);sp.renderOrder=4;g.add(sp)};
  lab('Mantle',-7.6,0);lab('Outer core',-3.75,0);lab('Inner core',0,0);
  this.pP=mkPts(NR*TR,.5,tex);this.pS=mkPts(NR*TR,.5,tex);this.eP=mkPts(NR,.8,tex);this.eS=mkPts(NR,.8,tex);
  this.lP=new THREE.LineSegments(new THREE.BufferGeometry(),new THREE.LineBasicMaterial({color:0xffa94d,transparent:true,opacity:.22}));
  this.lS=new THREE.LineSegments(new THREE.BufferGeometry(),new THREE.LineBasicMaterial({color:0xf472b6,transparent:true,opacity:.22}));
  this.fl=new THREE.Mesh(new THREE.SphereGeometry(.4,16,12),new THREE.MeshBasicMaterial({color:0xffffff,transparent:true}));
  this.ep=new THREE.Mesh(new THREE.RingGeometry(.35,.5,32),new THREE.MeshBasicMaterial({color:0xffffff,transparent:true,side:THREE.DoubleSide}));
  this.hs=new THREE.Group();const hb=new THREE.Mesh(new THREE.BoxGeometry(.45,.5,.45),mk(0xffb454,.6)),hr=new THREE.Mesh(new THREE.ConeGeometry(.42,.3,4),mk(0xff6b5a,.6));hb.position.y=.25;hr.position.y=.65;hr.rotation.y=Math.PI/4;this.hs.add(hb,hr);
  this.st=new THREE.Group();this.st.add(this.hs);g.add(this.lP,this.lS,this.pP,this.pS,this.eP,this.eS,this.fl,this.ep,this.st);this.quake([0,7.8]);return g},
 quake(F){const r=Math.hypot(F[0],F[1]),k=cl(r,5.9,9.7);F=[F[0]/r*k,F[1]/r*k];this.F=F;this.t0=t;this.fp=this.fs=0;shk=.3;this.RP=[];this.RS=[];const lp=[],ls=[];
  for(let i=0;i<NR;i++){const a=i/NR*PI2,d=[Math.cos(a),Math.sin(a)],rp=trace(F,d,false),rs=trace(F,d,true);this.RP.push(rp);this.RS.push(rs);
   if(i%4==0)[[rp,lp],[rs,ls]].forEach(([q,l])=>{for(let j=1;j<q.pts.length;j++)l.push(q.pts[j-1][0],q.pts[j-1][1],0,q.pts[j][0],q.pts[j][1],0)})}
  [[this.lP,lp],[this.lS,ls]].forEach(([l,a])=>{l.geometry.dispose();l.geometry=new THREE.BufferGeometry().setAttribute('position',new THREE.Float32BufferAttribute(a,3))});
  [[this.eP,this.RP],[this.eS,this.RS]].forEach(([p,Rs])=>{const a=p.geometry.attributes.position;Rs.forEach((q,i)=>a.setXYZ(i,q.end[0],q.end[1],.05));a.needsUpdate=true});
  this.fl.position.set(F[0],F[1],.1);this.ep.position.set(F[0]/k*ER,F[1]/k*ER,.1)},
 arr(){const a=P.eq.sa*Math.PI/180,f=Rs=>{let b=1e9,tm=null;for(const r of Rs){if(r.blocked)continue;const e=Math.atan2(r.end[1],r.end[0]),d=Math.abs(((e-a+3*Math.PI)%PI2)-Math.PI);if(d<b){b=d;tm=r.cum[r.cum.length-1]/3}}return b<.03?tm:null};return[f(this.RP),f(this.RS)]},
 sig(q,tp,ts,m){let a=0;if(tp!=null&&q>tp){const u=q-tp;a+=.3*m*Math.exp(-u*1.6)*Math.sin(u*14)}if(ts!=null&&q>ts){const u=q-ts;a+=m*Math.exp(-u*1.1)*Math.sin(u*9)}return a},
 upd(t){const p=P.eq,qt=t-this.t0,Tn=qt*3,m=p.mag,sP=p.seg!=2,sS=p.seg!=1;this.lP.visible=sP;this.lS.visible=sS;
  const fill=(pt,Rs,on,c)=>{const pa=pt.geometry.attributes.position,ca=pt.geometry.attributes.color;let n=0;for(const r of Rs)for(let j=0;j<TR;j++){const q=on?posAt(r,Tn-j*.22):null,w=q?1-j/TR:0;pa.setXYZ(n,q?q[0]:0,q?q[1]:0,.05);ca.setXYZ(n++,c[0]*w,c[1]*w,c[2]*w)}pa.needsUpdate=ca.needsUpdate=true};
  const ends=(pt,Rs,on,c)=>{const ca=pt.geometry.attributes.color;Rs.forEach((r,i)=>{const T=r.cum[r.cum.length-1],b=on&&Tn>T?Math.exp(-(Tn-T)/7.5)*(r.blocked?.5:1):0;ca.setXYZ(i,c[0]*b,c[1]*b,c[2]*b)});ca.needsUpdate=true};
  const cP=[1,.62,.2],cS=[1,.3,.65];fill(this.pP,this.RP,sP,cP);fill(this.pS,this.RS,sS,cS);ends(this.eP,this.RP,sP,cP);ends(this.eS,this.RS,sS,cS);
  this.pP.material.size=this.pS.material.size=.35+.35*m;
  const a=p.sa*Math.PI/180,[tp,ts]=this.arr();this.st.position.set(Math.cos(a)*ER,Math.sin(a)*ER,0);this.st.rotation.z=a-Math.PI/2;
  this.hs.position.x=this.sig(qt,tp,ts,m)*.3;
  if(tp!=null&&qt>=tp&&!this.fp){this.fp=1;shk=.12+.1*m;vib(25)}
  if(ts!=null&&qt>=ts&&!this.fs){this.fs=1;shk=.3+.25*m;vib([60,30,60])}
  this.fl.scale.setScalar(.3+2.5*Math.exp(-qt*3));this.fl.material.opacity=Math.exp(-qt*1.5);
  this.ep.scale.setScalar(1+qt*4);this.ep.material.opacity=Math.max(0,1-qt/1.2);
  const c=this.sgc;if(!c)return;const g=c.getContext('2d'),w=c.width,h=c.height,s=this.dpr,span=(ts||tp||5)*1.25+1.2;g.clearRect(0,0,w,h);
  g.strokeStyle='#16384a';g.lineWidth=s;g.beginPath();g.moveTo(0,h/2);g.lineTo(w,h/2);g.stroke();
  g.strokeStyle='#4fd8cf';g.lineWidth=1.5*s;g.beginPath();const px=Math.min(w,qt/span*w);
  for(let x=0;x<=px;x++){const y=h/2-this.sig(x/w*span,tp,ts,m)*h*.4;x?g.lineTo(x,y):g.moveTo(x,y)}g.stroke();
  g.font=(12*s)+'px IBM Plex Sans,sans-serif';[[tp,'P','#ffb454'],[ts,'S','#f472b6']].forEach(([q,l,col])=>{if(q!=null&&qt>=q){g.fillStyle=col;g.fillText(l,q/span*w+4*s,14*s)}});
  g.fillStyle='#86a9b4';g.fillText('Seismograph at the station',6*s,h-6*s);if(ts==null&&qt>2){g.fillStyle='#f472b6';g.fillText('No S-wave arrives',w-130*s,h-6*s)}},
 extra(ct){const c=document.createElement('canvas');c.style.cssText='width:100%;height:100px;border:1px solid var(--line);border-radius:10px;background:rgba(4,16,26,.5);margin-bottom:10px';ct.appendChild(c);
  this.dpr=Math.min(devicePixelRatio,2);c.width=(c.clientWidth||320)*this.dpr;c.height=100*this.dpr;this.sgc=c;
  const b=document.createElement('button');b.className='b';b.textContent='Random earthquake';b.style.marginBottom='12px';b.onclick=()=>{const a=Math.random()*PI2,r=6+Math.random()*3.5;this.quake([Math.cos(a)*r,Math.sin(a)*r])};ct.appendChild(b)},
 tap(e){const rc=cv.getBoundingClientRect(),ray=new THREE.Raycaster(),pt=new THREE.Vector3();ray.setFromCamera(new THREE.Vector2((e.clientX-rc.left)/rc.width*2-1,-(e.clientY-rc.top)/rc.height*2+1),cam);
  if(ray.ray.intersectPlane(new THREE.Plane(new THREE.Vector3(0,0,1),0),pt)&&Math.hypot(pt.x,pt.y)<12)this.quake([pt.x,pt.y])},
 read(){const p=P.eq,[tp,ts]=this.arr(),a=p.sa*Math.PI/180,e=Math.atan2(this.F[1],this.F[0]),dl=Math.abs(((e-a+3*Math.PI)%PI2)-Math.PI)*180/Math.PI,
  rt=s=>{const T=Math.round(s*239);return Math.floor(T/60)+' min '+String(T%60).padStart(2,'0')+' s'};
  return[['Distance to station',Math.round(dl*111).toLocaleString()+' km'],['Quake depth',Math.round((ER-Math.hypot(this.F[0],this.F[1]))*KM)+' km'],['P-wave arrives',tp==null?'Not directly (shadow zone)':rt(tp)],['S-wave arrives',ts==null?'Never: liquid core':rt(ts)],['S minus P gap',tp!=null&&ts!=null?rt(ts-tp):'No S-wave']]}};
cv.addEventListener('pointerdown',e=>dn=[e.clientX,e.clientY]);
cv.addEventListener('pointerup',e=>{if(dn&&cur&&cur.tap&&Math.hypot(e.clientX-dn[0],e.clientY-dn[1])<6)cur.tap(e);dn=null});

/* ---------- UI ---------- */
const ids=['med','oc','itf','em','eq'];
Object.keys(defs).forEach(k=>{P[k]={seg:0};defs[k].sl.forEach(s=>P[k][s[0]]=s[5])});
P.em.b=3;
const tabs=$('#tabs');
[...ids,'learn'].forEach(id=>{const b=document.createElement('button');b.className='tab';b.dataset.id=id;b.textContent=id=='learn'?'Learn & quiz':defs[id].name;b.onclick=()=>show(id);tabs.appendChild(b)});
let last='med';
function show(id){document.querySelectorAll('.tab').forEach(b=>b.classList.toggle('on',b.dataset.id==id));
 $('#learn').hidden=id!='learn';$('#lab').hidden=id=='learn';if(id=='learn'){$('#title').innerHTML='Wave field guide<small>Concepts, equations, quiz</small>';return}
 last=id;const d=defs[id];if(cur)sc.remove(cur.grp);if(!d.grp)d.grp=d.build();cur=d;sc.add(d.grp);
 [c3.th,c3.ph,c3.r]=d.cam;$('#title').innerHTML=d.name+'<small>'+d.sub+'</small>';
 const p=P[id],ct=$('#ctrl');ct.innerHTML='';
 if(d.seg){const s=document.createElement('div');s.className='seg';d.seg.forEach((n,i)=>{const b=document.createElement('button');b.className='b'+(p.seg==i?' on':'');b.textContent=n;b.onclick=()=>{p.seg=i;[...s.children].forEach((c,j)=>c.classList.toggle('on',j==i));note()};s.appendChild(b)});ct.appendChild(s)}
 if(d.chips){const s=document.createElement('div');s.className='seg';bands.forEach((bd,i)=>{const b=document.createElement('button');b.className='b chip'+(p.b==i?' on':'');b.textContent=bd[0];b.onclick=()=>{p.b=i;[...s.children].forEach((c,j)=>c.classList.toggle('on',j==i))};s.appendChild(b)});ct.appendChild(s)}
 d.sl.forEach(([k,lb,mn,mx,st,v])=>{const r=document.createElement('div');r.className='row';r.innerHTML='<div><span>'+lb+'</span><b></b></div><input type="range" min="'+mn+'" max="'+mx+'" step="'+st+'">';
  const i=r.querySelector('input'),o=r.querySelector('b');i.value=p[k];o.textContent=(+p[k]).toFixed(2);i.oninput=()=>{p[k]=+i.value;o.textContent=(+i.value).toFixed(2)};ct.appendChild(r)});
 if(d.extra)d.extra(ct);$('#hint').textContent=d.hint||'Drag to orbit. Pinch or scroll to zoom.';note();rd()}
const note=()=>$('#note').innerHTML=cur.note();
function rd(){$('#read').innerHTML=cur.read().map(r=>'<div><span>'+r[0]+'</span><b>'+r[1]+'</b></div>').join('')}

/* ---------- Quiz ---------- */
const Q=[['Which wave needs a material medium?',['Visible light','Sound','X-rays','Radio'],1,'Sound is mechanical. EM waves travel through vacuum.'],
['Amplitude doubles. What happens to the wave energy?',['Doubles','Triples','Quadruples','Stays the same'],2,'Energy grows with the square of the amplitude, so doubling it gives four times the energy.'],
['Light enters glass (n = 1.5). Which quantity stays the same?',['Speed','Wavelength','Frequency','All change'],2,'Frequency is set by the source. v and λ both drop by n.'],
['Two sources are in phase. At a point 1.5λ farther from one than the other you see…',['Constructive interference','Destructive interference','No wave','Doubled frequency'],1,'1.5 wavelengths is an odd number of half-wavelengths, so crest meets trough.'],
['Why can S-waves not cross the outer core of the Earth?',['It is too hot','It is liquid','It is too thick','They bounce off the crust'],1,'S-waves shake sideways and a liquid cannot pass that on, so they stop. That is how we know the outer core is liquid.'],
['In a sound wave, air molecules move…',['Perpendicular to travel','In circles only','Parallel to travel','Not at all'],2,'Sound is longitudinal: compressions and rarefactions.']];
let qi=0,qs=0;
function rq(){const q=$('#quiz');if(qi>=Q.length){q.innerHTML='<p><b>Score: '+qs+' / '+Q.length+'.</b> '+(qs==Q.length?'Perfect. You can read waves.':'Revisit the tabs and try again.')+'</p><button class="b" id="rs">Restart</button>';$('#rs').onclick=()=>{qi=qs=0;rq()};return}
 const x=Q[qi];q.innerHTML='<div class="q"><b>'+(qi+1)+'. '+x[0]+'</b>'+x[1].map((a,i)=>'<button data-i="'+i+'">'+a+'</button>').join('')+'<div class="ex"></div></div>';
 q.querySelectorAll('button').forEach(b=>b.onclick=()=>{const ok=+b.dataset.i==x[2];if(ok)qs++;b.classList.add(ok?'ok':'no');q.querySelectorAll('button')[x[2]].classList.add('ok');q.querySelectorAll('button').forEach(z=>z.onclick=null);
  q.querySelector('.ex').innerHTML=x[3]+' <button class="b" id="nx" style="display:inline-block;width:auto;margin-left:6px">Next</button>';$('#nx').onclick=()=>{qi++;rq()}})}
rq();

/* ---------- Loop ---------- */
let prev=performance.now();
function loop(now){requestAnimationFrame(loop);const dt=Math.min((now-prev)/1000,.05);prev=now;if(!paused)t+=dt*(slow?.25:1);
 cam.position.set(c3.r*Math.sin(c3.ph)*Math.sin(c3.th),c3.r*Math.cos(c3.ph),c3.r*Math.sin(c3.ph)*Math.cos(c3.th));if(shk>.004){cam.position.x+=(Math.random()-.5)*shk;cam.position.y+=(Math.random()-.5)*shk;shk*=.93}cam.lookAt(0,0,0);
 if(cur){cur.upd(t);if(++fr%8==0&&!$('#lab').hidden)rd()}R.render(sc,cam)}
show('med');size();requestAnimationFrame(loop);
</script></body></html>
