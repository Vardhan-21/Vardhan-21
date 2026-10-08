<svg width="1600" height="760" viewBox="0 0 1600 760" xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="title desc">
<title>Jaya Vardhan Nidizivvi — Cloud DevOps Command Center</title>
<desc>Futuristic 3D hero with glass identity card, floating infrastructure nodes, perspective grid and animated data pipelines</desc>
<defs>
  <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%" stop-color="#040A1E"/>
    <stop offset="50%" stop-color="#0A1B3A"/>
    <stop offset="100%" stop-color="#050814"/>
  </linearGradient>
  <linearGradient id="cardFill" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%" stop-color="#0F2340" stop-opacity="0.95"/>
    <stop offset="100%" stop-color="#0A1430" stop-opacity="0.9"/>
  </linearGradient>
  <linearGradient id="cyanGrad" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="#00E5FF"/>
    <stop offset="100%" stop-color="#7B61FF"/>
  </linearGradient>
  <linearGradient id="borderGrad" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="#00E5FF" stop-opacity="0.9"/>
    <stop offset="50%" stop-color="#7C4DFF" stop-opacity="0.9"/>
    <stop offset="100%" stop-color="#FF2E93" stop-opacity="0.8"/>
  </linearGradient>
  <radialGradient id="glowCyan" cx="50%" cy="50%" r="50%">
    <stop offset="0%" stop-color="#00E5FF" stop-opacity="0.35"/>
    <stop offset="100%" stop-color="#00E5FF" stop-opacity="0"/>
  </radialGradient>
  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="6" result="blur"/>
    <feComposite in="SourceGraphic" in2="blur" operator="over"/>
    <feDropShadow dx="0" dy="0" stdDeviation="8" flood-color="#00E5FF" flood-opacity="0.5"/>
  </filter>
  <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3.5" result="b"/>
    <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <pattern id="gridSmall" width="40" height="40" patternUnits="userSpaceOnUse">
    <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#1E3A5F" stroke-opacity="0.15" stroke-width="1"/>
  </pattern>
</defs>

<!-- BACKGROUND -->
<rect width="1600" height="760" fill="url(#bg)"/>
<rect width="1600" height="760" fill="url(#gridSmall)" opacity="0.6"/>

<!-- Ambient glows -->
<circle cx="300" cy="120" r="280" fill="url(#glowCyan)" opacity="0.25"/>
<circle cx="1320" cy="180" r="320" fill="url(#glowCyan)" opacity="0.18" style="fill: url(#glowCyan)"/>
<circle cx="800" cy="700" r="500" fill="#7C4DFF" opacity="0.06"/>

<!-- PERSPECTIVE GRID FLOOR -->
<g opacity="0.9">
  <!-- horizon line -->
  <line x1="0" y1="580" x2="1600" y2="580" stroke="#00E5FF" stroke-opacity="0.18" stroke-width="1.5"/>
  <!-- converging lines -->
  <path d="M 800 380 L 0 760" stroke="#1E4A7A" stroke-opacity="0.25" stroke-width="1"/>
  <path d="M 800 380 L 260 760" stroke="#1E4A7A" stroke-opacity="0.22" stroke-width="1"/>
  <path d="M 800 380 L 520 760" stroke="#1E4A7A" stroke-opacity="0.20" stroke-width="1"/>
  <path d="M 800 380 L 800 760" stroke="#00E5FF" stroke-opacity="0.15" stroke-width="1.2"/>
  <path d="M 800 380 L 1080 760" stroke="#1E4A7A" stroke-opacity="0.20" stroke-width="1"/>
  <path d="M 800 380 L 1340 760" stroke="#1E4A7A" stroke-opacity="0.22" stroke-width="1"/>
  <path d="M 800 380 L 1600 760" stroke="#1E4A7A" stroke-opacity="0.25" stroke-width="1"/>
  <!-- horizontal floor lines -->
  <line x1="120" y1="620" x2="1480" y2="620" stroke="#1A3A5A" stroke-opacity="0.35" stroke-width="1"/>
  <line x1="70" y1="660" x2="1530" y2="660" stroke="#1A3A5A" stroke-opacity="0.30" stroke-width="1"/>
  <line x1="20" y1="705" x2="1580" y2="705" stroke="#1A3A5A" stroke-opacity="0.28" stroke-width="1"/>
  <line x1="0" y1="750" x2="1600" y2="750" stroke="#1A3A5A" stroke-opacity="0.22" stroke-width="1"/>
</g>

<!-- TOP HUD -->
<g font-family="\'JetBrains Mono\',Consolas,monospace">
  <text x="40" y="36" font-size="11" fill="#00E5FF" letter-spacing="3.5" opacity="0.95">◉ DEVOPS COMMAND CENTER // SYS.STATUS: OPERATIONAL</text>
  <text x="1240" y="36" font-size="11" fill="#7B61FF" letter-spacing="2.5" opacity="0.9">PROVISION → BUILD → DEPLOY → OBSERVE</text>
  <rect x="40" y="48" width="320" height="1.5" fill="url(#cyanGrad)" opacity="0.7"/>
  <rect x="1240" y="48" width="320" height="1.5" fill="url(#cyanGrad)" opacity="0.4"/>
</g>

<!-- CONNECTION PIPELINES (behind cards) -->
<g fill="none" stroke-linecap="round">
  <path id="p1" d="M 330 185 C 450 210, 520 260, 575 335" stroke="#1E3A5F" stroke-width="3.5" opacity="0.9"/>
  <path d="M 330 185 C 450 210, 520 260, 575 335" stroke="url(#cyanGrad)" stroke-width="1.6" stroke-dasharray="8 10" opacity="0.95">
    <animate attributeName="stroke-dashoffset" from="0" to="36" dur="1.2s" repeatCount="indefinite"/>
  </path>
  <path id="p2" d="M 520 135 C 620 170, 640 250, 650 315" stroke="#1E3A5F" stroke-width="3.5" opacity="0.9"/>
  <path d="M 520 135 C 620 170, 640 250, 650 315" stroke="url(#cyanGrad)" stroke-width="1.6" stroke-dasharray="8 10" opacity="0.95">
    <animate attributeName="stroke-dashoffset" from="0" to="36" dur="1.1s" repeatCount="indefinite"/>
  </path>
  <path id="p3" d="M 1065 150 C 980 190, 910 250, 850 315" stroke="#1E3A5F" stroke-width="3.5" opacity="0.9"/>
  <path d="M 1065 150 C 980 190, 910 250, 850 315" stroke="url(#cyanGrad)" stroke-width="1.6" stroke-dasharray="8 10" opacity="0.95">
    <animate attributeName="stroke-dashoffset" from="36" to="0" dur="1.3s" repeatCount="indefinite"/>
  </path>
  <path id="p4" d="M 1215 205 C 1100 250, 990 290, 890 355" stroke="#1E3A5F" stroke-width="3.5" opacity="0.9"/>
  <path d="M 1215 205 C 1100 250, 990 290, 890 355" stroke="#7B61FF" stroke-width="1.6" stroke-dasharray="8 10" opacity="0.9">
    <animate attributeName="stroke-dashoffset" from="0" to="36" dur="1.25s" repeatCount="indefinite"/>
  </path>
  <path id="p5" d="M 1190 445 C 1080 410, 960 380, 890 385" stroke="#1E3A5F" stroke-width="3.5" opacity="0.9"/>
  <path d="M 1190 445 C 1080 410, 960 380, 890 385" stroke="#7B61FF" stroke-width="1.6" stroke-dasharray="8 10" opacity="0.9">
    <animate attributeName="stroke-dashoffset" from="36" to="0" dur="1.15s" repeatCount="indefinite"/>
  </path>
  <path id="p6" d="M 985 525 C 920 470, 860 420, 830 395" stroke="#1E3A5F" stroke-width="3.5" opacity="0.9"/>
  <path d="M 985 525 C 920 470, 860 420, 830 395" stroke="url(#cyanGrad)" stroke-width="1.6" stroke-dasharray="8 10" opacity="0.95">
    <animate attributeName="stroke-dashoffset" from="0" to="36" dur="1.2s" repeatCount="indefinite"/>
  </path>
  <path id="p7" d="M 420 485 C 500 450, 590 400, 680 390" stroke="#1E3A5F" stroke-width="3.5" opacity="0.9"/>
  <path d="M 420 485 C 500 450, 590 400, 680 390" stroke="url(#cyanGrad)" stroke-width="1.6" stroke-dasharray="8 10" opacity="0.95">
    <animate attributeName="stroke-dashoffset" from="36" to="0" dur="1.3s" repeatCount="indefinite"/>
  </path>
</g>

<!-- DATA PACKETS (animated along pipes) -->
<g filter="url(#glow)">
  <circle r="5.5" fill="#00E5FF"><animateMotion dur="2.2s" repeatCount="indefinite" rotate="auto"><mpath href="#p1"/></animateMotion></circle>
  <circle r="5" fill="#FFFFFF"><animateMotion dur="2.0s" repeatCount="indefinite" begin="0.4s" rotate="auto"><mpath href="#p2"/></animateMotion></circle>
  <circle r="5.5" fill="#7B61FF"><animateMotion dur="2.4s" repeatCount="indefinite" rotate="auto"><mpath href="#p3"/></animateMotion></circle>
  <circle r="5" fill="#00FF94"><animateMotion dur="2.1s" repeatCount="indefinite" begin="0.3s" rotate="auto"><mpath href="#p4"/></animateMotion></circle>
  <circle r="5.5" fill="#FF2E93"><animateMotion dur="2.3s" repeatCount="indefinite" rotate="auto"><mpath href="#p5"/></animateMotion></circle>
  <circle r="4.5" fill="#00E5FF"><animateMotion dur="2.0s" repeatCount="indefinite" begin="0.6s" rotate="auto"><mpath href="#p6"/></animateMotion></circle>
  <circle r="5" fill="#FFB800"><animateMotion dur="2.2s" repeatCount="indefinite" begin="0.2s" rotate="auto"><mpath href="#p7"/></animateMotion></circle>
</g>

<!-- FLOATING INFRA NODES -->
<g font-family="\'JetBrains Mono\',Consolas,monospace">
  <!-- Node: Terraform -->
  <g filter="url(#softGlow)">
    <rect x="210" y="145" width="150" height="62" rx="14" fill="#0C1E3A" stroke="#7B61FF" stroke-opacity="0.7" stroke-width="1.3"/>
    <rect x="210" y="145" width="150" height="62" rx="14" fill="none" stroke="#7B61FF" stroke-opacity="0.15" stroke-width="8"/>
    <circle cx="232" cy="176" r="14" fill="#7B61FF" opacity="0.95"/><text x="232" y="181" text-anchor="middle" font-size="13" fill="#fff">◈</text>
    <text x="254" y="172" font-size="10.5" fill="#8EA0C2" letter-spacing="1.5">INFRA</text>
    <text x="254" y="189" font-size="13.5" fill="#FFFFFF" font-weight="700" letter-spacing="1">TERRAFORM</text>
    <circle cx="348" cy="158" r="4" fill="#00FF94"><animate attributeName="opacity" values="1;0.3;1" dur="1.6s" repeatCount="indefinite"/></circle>
  </g>
  <!-- Node: AWS -->
  <g filter="url(#softGlow)">
    <rect x="430" y="98" width="135" height="62" rx="14" fill="#0C1E3A" stroke="#FF9900" stroke-opacity="0.7" stroke-width="1.3"/>
    <circle cx="452" cy="129" r="14" fill="#FF9900"/><text x="452" y="134" text-anchor="middle" font-size="11" fill="#0A1220" font-weight="800">aws</text>
    <text x="474" y="125" font-size="10.5" fill="#8EA0C2" letter-spacing="1.5">CLOUD</text>
    <text x="474" y="142" font-size="13.5" fill="#FFFFFF" font-weight="700" letter-spacing="1">AWS</text>
    <circle cx="553" cy="111" r="4" fill="#00FF94"><animate attributeName="opacity" values="1;0.2;1" dur="1.4s" repeatCount="indefinite"/></circle>
  </g>
  <!-- Node: Docker -->
  <g filter="url(#softGlow)">
    <rect x="980" y="108" width="140" height="62" rx="14" fill="#0C1E3A" stroke="#0DB7ED" stroke-opacity="0.7" stroke-width="1.3"/>
    <circle cx="1002" cy="139" r="14" fill="#0DB7ED"/><text x="1002" y="144" text-anchor="middle" font-size="13" fill="#fff">⬢</text>
    <text x="1024" y="135" font-size="10.5" fill="#8EA0C2" letter-spacing="1.5">CONTAINER</text>
    <text x="1024" y="152" font-size="13.5" fill="#FFFFFF" font-weight="700" letter-spacing="1">DOCKER</text>
    <circle cx="1108" cy="121" r="4" fill="#00FF94"><animate attributeName="opacity" values="1;0.3;1" dur="1.8s" repeatCount="indefinite"/></circle>
  </g>
  <!-- Node: Kubernetes -->
  <g filter="url(#softGlow)">
    <rect x="1100" y="170" width="175" height="62" rx="14" fill="#0C1E3A" stroke="#326CE5" stroke-opacity="0.75" stroke-width="1.3"/>
    <circle cx="1122" cy="201" r="14" fill="#326CE5"/><text x="1122" y="206" text-anchor="middle" font-size="12" fill="#fff">☸</text>
    <text x="1144" y="197" font-size="10.5" fill="#8EA0C2" letter-spacing="1.5">ORCHESTRATION</text>
    <text x="1144" y="214" font-size="13.5" fill="#FFFFFF" font-weight="700" letter-spacing="0.8">KUBERNETES</text>
    <circle cx="1263" cy="183" r="4" fill="#00FF94"><animate attributeName="opacity" values="1;0.25;1" dur="1.5s" repeatCount="indefinite"/></circle>
  </g>
  <!-- Node: Jenkins -->
  <g filter="url(#softGlow)">
    <rect x="1085" y="410" width="150" height="62" rx="14" fill="#0C1E3A" stroke="#D33833" stroke-opacity="0.65" stroke-width="1.3"/>
    <circle cx="1107" cy="441" r="14" fill="#1A1A1A" stroke="#D33833" stroke-width="1.2"/><text x="1107" y="446" text-anchor="middle" font-size="11" fill="#D33833" font-weight="800">J</text>
    <text x="1129" y="437" font-size="10.5" fill="#8EA0C2" letter-spacing="1.5">CI/CD</text>
    <text x="1129" y="454" font-size="13.5" fill="#FFFFFF" font-weight="700" letter-spacing="1">JENKINS</text>
    <circle cx="1223" cy="423" r="4" fill="#00FF94"><animate attributeName="opacity" values="1;0.3;1" dur="1.7s" repeatCount="indefinite"/></circle>
  </g>
  <!-- Node: Prometheus -->
  <g filter="url(#softGlow)">
    <rect x="905" y="490" width="175" height="62" rx="14" fill="#0C1E3A" stroke="#E6522C" stroke-opacity="0.65" stroke-width="1.3"/>
    <circle cx="927" cy="521" r="14" fill="#E6522C"/><text x="927" y="526" text-anchor="middle" font-size="11" fill="#fff">◉</text>
    <text x="949" y="517" font-size="10.5" fill="#8EA0C2" letter-spacing="1.5">METRICS</text>
    <text x="949" y="534" font-size="13.5" fill="#FFFFFF" font-weight="700" letter-spacing="0.8">PROMETHEUS</text>
    <circle cx="1068" cy="503" r="4" fill="#00FF94"><animate attributeName="opacity" values="1;0.25;1" dur="1.6s" repeatCount="indefinite"/></circle>
  </g>
  <!-- Node: Grafana -->
  <g filter="url(#softGlow)">
    <rect x="305" y="445" width="150" height="62" rx="14" fill="#0C1E3A" stroke="#F46800" stroke-opacity="0.65" stroke-width="1.3"/>
    <circle cx="327" cy="476" r="14" fill="#F46800"/><text x="327" y="481" text-anchor="middle" font-size="12" fill="#fff">⬣</text>
    <text x="349" y="472" font-size="10.5" fill="#8EA0C2" letter-spacing="1.5">VISUALIZE</text>
    <text x="349" y="489" font-size="13.5" fill="#FFFFFF" font-weight="700" letter-spacing="1">GRAFANA</text>
    <circle cx="443" cy="458" r="4" fill="#00FF94"><animate attributeName="opacity" values="1;0.2;1" dur="1.9s" repeatCount="indefinite"/></circle>
  </g>
</g>

<!-- CENTRAL 3D IDENTITY CARD (isometric base shadow) -->
<g opacity="0.5">
  <path d="M 545 545 L 575 565 L 1055 565 L 1025 545 Z" fill="#020816"/>
  <path d="M 1025 545 L 1055 565 L 1055 285 L 1025 265 Z" fill="#081530"/>
</g>

<!-- Main Card -->
<g filter="url(#glow)">
  <rect x="545" y="225" width="510" height="320" rx="22" fill="url(#cardFill)" stroke="url(#borderGrad)" stroke-width="1.6"/>
  <!-- inner top highlight -->
  <rect x="545" y="225" width="510" height="1.8" rx="22" fill="#00E5FF" opacity="0.7"/>
  <!-- glass reflection -->
  <rect x="545" y="225" width="510" height="160" rx="22" fill="white" opacity="0.03"/>
  
  <!-- status bar inside -->
  <g font-family="\'JetBrains Mono\',Consolas,monospace">
    <rect x="575" y="250" width="450" height="26" rx="13" fill="#07152E" stroke="#143055" stroke-width="1"/>
    <circle cx="590" cy="263" r="5" fill="#00FF94"><animate attributeName="opacity" values="1;0.4;1" dur="1.2s" repeatCount="indefinite"/></circle>
    <text x="602" y="267.5" font-size="9.5" fill="#00FF94" letter-spacing="2" font-weight="700">SYSTEM ONLINE • CLOUD NATIVE • PRODUCTION READY</text>
    <circle cx="1008" cy="263" r="3" fill="#00E5FF" opacity="0.9"/>
    <circle cx="1016" cy="263" r="3" fill="#7B61FF" opacity="0.9"/>
    <circle cx="1024" cy="263" r="3" fill="#FF2E93" opacity="0.9"/>
  </g>

  <!-- Name -->
  <g text-anchor="middle" font-family="\'Inter\',\'Segoe UI\',Helvetica,Arial,sans-serif">
    <text x="800" y="322" font-size="42" font-weight="900" fill="#FFFFFF" letter-spacing="6" style="filter: drop-shadow(0 0 12px rgba(0,229,255,0.5))">JAYA VARDHAN</text>
    <text x="800" y="362" font-size="42" font-weight="900" fill="none" stroke="#00E5FF" stroke-width="1.1" letter-spacing="6" opacity="0.95">NIDIZIVVI</text>
    <rect x="685" y="378" width="230" height="2" fill="url(#cyanGrad)" opacity="0.9"/>
  </g>

  <g font-family="\'JetBrains Mono\',Consolas,monospace" text-anchor="middle">
    <text x="800" y="405" font-size="13.5" fill="#00E5FF" letter-spacing="4.5" font-weight="700">CLOUD / DEVOPS ENGINEER</text>
    <text x="800" y="432" font-size="10.8" fill="#A0B2D0" letter-spacing="2.2">AWS • TERRAFORM • DOCKER • KUBERNETES • JENKINS • OBSERVABILITY</text>
  </g>

  <!-- bottom tech mini pills -->
  <g font-family="\'JetBrains Mono\',Consolas,monospace" text-anchor="middle">
    <rect x="575" y="455" width="152" height="28" rx="14" fill="#0B1E3B" stroke="#00E5FF" stroke-opacity="0.35"/>
    <text x="651" y="473" font-size="9.5" fill="#7ED8FF" letter-spacing="1.2" font-weight="700">INFRA AS CODE</text>
    <rect x="742" y="455" width="152" height="28" rx="14" fill="#0B1E3B" stroke="#7B61FF" stroke-opacity="0.35"/>
    <text x="818" y="473" font-size="9.5" fill="#B8A6FF" letter-spacing="1.2" font-weight="700">CONTAINERS @ SCALE</text>
    <rect x="909" y="455" width="116" height="28" rx="14" fill="#0B1E3B" stroke="#00FF94" stroke-opacity="0.35"/>
    <text x="967" y="473" font-size="9.5" fill="#7BFFC8" letter-spacing="1.2" font-weight="700">AUTO-HEAL</text>
  </g>

  <!-- micro telemetry -->
  <g font-family="\'JetBrains Mono\',Consolas,monospace" opacity="0.95">
    <text x="575" y="510" font-size="8.5" fill="#5A7090" letter-spacing="1.2">LATENCY ▁▂▃▅▃▂▁ • HEALTH  ● OPTIMAL • REGION ap-south-1</text>
    <text x="905" y="510" font-size="8.5" fill="#5A7090" letter-spacing="1.2">UPTIME 99.95% • PIPELINE ACTIVE</text>
  </g>
</g>

<!-- FLOATING PARTICLES -->
<g opacity="0.9">
  <circle cx="640" cy="600" r="1.8" fill="#00E5FF" opacity="0.7"><animate attributeName="cy" values="600;585;600" dur="3s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.7;0.2;0.7" dur="3s" repeatCount="indefinite"/></circle>
  <circle cx="980" cy="610" r="1.6" fill="#7B61FF" opacity="0.6"><animate attributeName="cy" values="610;595;610" dur="3.6s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.6;0.2;0.6" dur="3.6s" repeatCount="indefinite"/></circle>
  <circle cx="760" cy="625" r="1.4" fill="#FFFFFF" opacity="0.5"><animate attributeName="cy" values="625;612;625" dur="2.8s" repeatCount="indefinite"/></circle>
  <circle cx="1120" cy="595" r="1.5" fill="#00FF94" opacity="0.6"><animate attributeName="cy" values="595;582;595" dur="3.2s" repeatCount="indefinite"/></circle>
  <circle cx="440" cy="605" r="1.3" fill="#FF2E93" opacity="0.5"><animate attributeName="cy" values="605;592;605" dur="3.4s" repeatCount="indefinite"/></circle>
</g>

<!-- BOTTOM LABEL -->
<g font-family="\'JetBrains Mono\',Consolas,monospace" text-anchor="middle" opacity="0.95">
  <text x="800" y="710" font-size="10" fill="#5A7090" letter-spacing="3">I BUILD AND OPERATE CLOUD INFRASTRUCTURE • PROVISION → BUILD → CONTAINERIZE → DEPLOY → ORCHESTRATE → OBSERVE</text>
  <rect x="760" y="720" width="80" height="1.2" fill="#00E5FF" opacity="0.6"/>
</g>
</svg>
