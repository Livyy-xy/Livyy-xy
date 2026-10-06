<!--
  Profile README in the "ACE" dark neon style, built for readme-aura.
  Edit the values marked EDIT, then run:  npx readme-aura build
-->

```aura width=800 height=260
<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', background: 'linear-gradient(180deg, #07070d 0%, #0d0a1f 100%)', borderRadius: 24, position: 'relative' }}>
  <svg width="800" height="260" viewBox="0 0 800 260" style={{ position: 'absolute', top: 0, left: 0 }}>
    <style>{`
      @keyframes breathe { 0%,100% { opacity: .35; transform: scale(1); } 50% { opacity: .75; transform: scale(1.12); } }
      #glowA { animation: breathe 5s ease-in-out infinite; transform-origin: 250px 120px; }
      #glowB { animation: breathe 7s ease-in-out infinite reverse; transform-origin: 560px 150px; }
    `}</style>
    <ellipse id="glowA" cx="250" cy="120" rx="170" ry="70" fill="#7c3aed" opacity="0.4" />
    <ellipse id="glowB" cx="560" cy="150" rx="150" ry="60" fill="#06b6d4" opacity="0.3" />
  </svg>
  <div style={{ display: 'flex', fontSize: 68, fontWeight: 800, letterSpacing: 18, color: '#ffffff' }}>LIVY</div>
  <div style={{ display: 'flex', marginTop: 12, fontSize: 15, letterSpacing: 9, color: '#a78bfa' }}>SYSTEMS PROGRAMMER</div>
  <div style={{ display: 'flex', marginTop: 18, fontSize: 12, letterSpacing: 4, color: '#8b8fa8' }}>PERFORMANCE ENGINEER | DEVOPS</div>
  <div style={{ display: 'flex', marginTop: 8, fontSize: 11, letterSpacing: 3, color: '#5eead4' }}>KERNEL INTERNALS  /  BARE-METAL  /  SOC VALIDATION</div>
</div>
```

```aura width=96 height=32 inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', borderRadius: 16, border: '1px solid #38bdf8', background: '#0b1220', color: '#38bdf8', fontSize: 13 }}>C</div>
```
```aura width=96 height=32 inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', borderRadius: 16, border: '1px solid #a78bfa', background: '#120d24', color: '#a78bfa', fontSize: 13 }}>C++</div>
```
```aura width=96 height=32 inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', borderRadius: 16, border: '1px solid #f472b6', background: '#1f0d19', color: '#f472b6', fontSize: 13 }}>Rust</div>
```
```aura width=96 height=32 inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', borderRadius: 16, border: '1px solid #5eead4', background: '#0a1a1a', color: '#5eead4', fontSize: 13 }}>Python</div>
```
```aura width=96 height=32 inline align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', borderRadius: 16, border: '1px solid #fbbf24', background: '#1c1507', color: '#fbbf24', fontSize: 13 }}>JavaScript</div>
```

```aura width=800 height=130
<div style={{ display: 'flex', justifyContent: 'space-around', alignItems: 'center', width: '100%', height: '100%', background: '#07070d', borderRadius: 20 }}>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
    <div style={{ display: 'flex', fontSize: 44, fontWeight: 800, color: '#fff' }}>41</div>
    <div style={{ display: 'flex', fontSize: 11, letterSpacing: 4, color: '#fbbf24' }}>STARS</div>
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
    <div style={{ display: 'flex', fontSize: 44, fontWeight: 800, color: '#fff' }}>4</div>
    <div style={{ display: 'flex', fontSize: 11, letterSpacing: 4, color: '#a78bfa' }}>FORKS</div>
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
    <div style={{ display: 'flex', fontSize: 44, fontWeight: 800, color: '#fff' }}>62</div>
    <div style={{ display: 'flex', fontSize: 11, letterSpacing: 4, color: '#5eead4' }}>REPOS</div>
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
    <div style={{ display: 'flex', fontSize: 44, fontWeight: 800, color: '#fff' }}>966</div>
    <div style={{ display: 'flex', fontSize: 11, letterSpacing: 4, color: '#f472b6' }}>COMMITS</div>
  </div>
</div>
```

```aura width=800 height=170
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', padding: 28, background: '#07070d', borderRadius: 20 }}>
  <div style={{ display: 'flex', fontSize: 12, letterSpacing: 5, color: '#38bdf8', marginBottom: 16 }}>STACK ANALYTICS</div>
  <div style={{ display: 'flex', width: '100%', height: 10, borderRadius: 5, overflow: 'hidden' }}>
    <div style={{ display: 'flex', width: '38%', background: '#f43f5e' }} />
    <div style={{ display: 'flex', width: '22%', background: '#a78bfa' }} />
    <div style={{ display: 'flex', width: '16%', background: '#38bdf8' }} />
    <div style={{ display: 'flex', width: '14%', background: '#5eead4' }} />
    <div style={{ display: 'flex', width: '10%', background: '#fbbf24' }} />
  </div>
  <div style={{ display: 'flex', marginTop: 20, fontSize: 13, color: '#c4c7d8' }}>
    <div style={{ display: 'flex', width: '20%', color: '#f43f5e' }}>C++ 38%</div>
    <div style={{ display: 'flex', width: '20%', color: '#a78bfa' }}>C 22%</div>
    <div style={{ display: 'flex', width: '20%', color: '#38bdf8' }}>TypeScript 16%</div>
    <div style={{ display: 'flex', width: '20%', color: '#5eead4' }}>Python 14%</div>
    <div style={{ display: 'flex', width: '20%', color: '#fbbf24' }}>Other 10%</div>
  </div>
</div>
```

```aura width=250 height=130 inline align=center link="https://github.com/Livyy-xy/PROJECT_ONE"
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', padding: 18, borderRadius: 16, border: '1px solid #2a2450', background: 'linear-gradient(160deg, #110d26, #07070d)' }}>
  <div style={{ display: 'flex', fontSize: 16, fontWeight: 700, color: '#fff' }}>Project One</div>
  <div style={{ display: 'flex', marginTop: 8, fontSize: 11, color: '#8b8fa8' }}>An operating system from scratch</div>
  <div style={{ display: 'flex', marginTop: 'auto', fontSize: 11, color: '#38bdf8' }}>C   ★ 12</div>
</div>
```
```aura width=250 height=130 inline align=center link="https://github.com/Livyy-xy/PROJECT_TWO"
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', padding: 18, borderRadius: 16, border: '1px solid #2a2450', background: 'linear-gradient(160deg, #110d26, #07070d)' }}>
  <div style={{ display: 'flex', fontSize: 16, fontWeight: 700, color: '#fff' }}>Project Two</div>
  <div style={{ display: 'flex', marginTop: 8, fontSize: 11, color: '#8b8fa8' }}>Programming language, compiler included</div>
  <div style={{ display: 'flex', marginTop: 'auto', fontSize: 11, color: '#a78bfa' }}>C++   ★ 8</div>
</div>
```
```aura width=250 height=130 inline align=center link="https://github.com/Livyy-xy/PROJECT_THREE"
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', padding: 18, borderRadius: 16, border: '1px solid #2a2450', background: 'linear-gradient(160deg, #110d26, #07070d)' }}>
  <div style={{ display: 'flex', fontSize: 16, fontWeight: 700, color: '#fff' }}>Project Three</div>
  <div style={{ display: 'flex', marginTop: 8, fontSize: 11, color: '#8b8fa8' }}>Lightweight game engine</div>
  <div style={{ display: 'flex', marginTop: 'auto', fontSize: 11, color: '#f472b6' }}>C++   ★ 4</div>
</div>
```
