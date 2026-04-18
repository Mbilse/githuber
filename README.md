# <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 580" width="100%" height="100%">
  <defs>
    <!-- 背景渐变 -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#6c5ce7"/>
      <stop offset="100%" stop-color="#a363d9"/>
    </linearGradient>
  </defs>

  <!-- 背景底板（圆角方形，类似应用图标） -->
  <rect width="512" height="580" rx="112" fill="url(#bgGrad)" />
  
  <!-- 落地阴影，增加立体感 -->
  <ellipse cx="256" cy="335" rx="80" ry="10" fill="#2d3436" opacity="0.15" />

  <!-- 右上角 IDE 标记 -->
  <rect x="370" y="40" width="110" height="34" rx="17" fill="#ff7675" />
  <text x="425" y="62" font-family="system-ui, -apple-system, sans-serif" font-size="16" font-weight="800" fill="#ffffff" text-anchor="middle">IDE</text>

  <!-- 章鱼触手（左侧） -->
  <path d="M 156 170 Q 60 170 70 90" stroke="#ffffff" stroke-width="24" stroke-linecap="round" fill="none" />
  <path d="M 156 220 Q 50 220 60 140" stroke="#ffffff" stroke-width="24" stroke-linecap="round" fill="none" />

  <!-- 章鱼触手（右侧） -->
  <path d="M 356 170 Q 452 170 442 90" stroke="#ffffff" stroke-width="24" stroke-linecap="round" fill="none" />
  <path d="M 356 220 Q 462 220 452 140" stroke="#ffffff" stroke-width="24" stroke-linecap="round" fill="none" />

  <!-- 触手上的吸盘（细节装饰） -->
  <!-- 左侧触手吸盘 -->
  <circle cx="130" cy="170" r="4" fill="#ffffff" opacity="0.4" />
  <circle cx="90" cy="130" r="4" fill="#ffffff" opacity="0.4" />
  <circle cx="130" cy="220" r="4" fill="#ffffff" opacity="0.4" />
  <circle cx="90" cy="180" r="4" fill="#ffffff" opacity="0.4" />
  
  <!-- 右侧触手吸盘 -->
  <circle cx="382" cy="170" r="4" fill="#ffffff" opacity="0.4" />
  <circle cx="422" cy="130" r="4" fill="#ffffff" opacity="0.4" />
  <circle cx="382" cy="220" r="4" fill="#ffffff" opacity="0.4" />
  <circle cx="422" cy="180" r="4" fill="#ffffff" opacity="0.4" />

  <!-- 章鱼头部（圆角方形，类似 GitHub 风格） -->
  <rect x="146" y="140" width="220" height="180" rx="90" fill="#ffffff" />

  <!-- 顶部代码光标（代表 IDE 编辑器） -->
  <path d="M 238 50 L 253 65 L 238 80" stroke="#ffffff" stroke-width="12" stroke-linecap="round" stroke-linejoin="round" fill="none" />
  <path d="M 274 50 L 259 65 L 274 80" stroke="#ffffff" stroke-width="12" stroke-linecap="round" stroke-linejoin="round" fill="none" />
  <line x1="264" y1="50" x2="264" y2="80" stroke="#ffffff" stroke-width="12" stroke-linecap="round" />

  <!-- 章鱼眼睛（使用代码括号风格，突出 Githuber 属性） -->
  <!-- 左眼：< -->
  <path d="M 205 205 L 185 225 L 205 245" stroke="#2d3436" stroke-width="12" stroke-linecap="round" stroke-linejoin="round" fill="none" />
  
  <!-- 右眼：/> -->
  <path d="M 305 205 L 325 225 L 305 245" stroke="#2d3436" stroke-width="12" stroke-linecap="round" stroke-linejoin="round" fill="none" />
  <line x1="318" y1="205" x2="318" y2="245" stroke="#2d3436" stroke-width="12" stroke-linecap="round" />

  <!-- 章鱼嘴巴（自信的微笑） -->
  <path d="M 235 275 Q 256 295 277 275" stroke="#2d3436" stroke-width="12" stroke-linecap="round" fill="none" />

  <!-- 主标题：GITHUBER -->
  <text x="256" y="500" font-family="system-ui, -apple-system, sans-serif" font-size="56" font-weight="900" fill="#ffffff" text-anchor="middle" letter-spacing="4">GITHUBER</text>

  <!-- 副标题：GitHub 管理 IDE -->
  <text x="256" y="540" font-family="system-ui, -apple-system, sans-serif" font-size="20" font-weight="600" fill="rgba(255,255,255,0.85)" text-anchor="middle" letter-spacing="6">GITHUB 管理 IDE</text>
</svg>
# Githuber IDE
Github IDE风格管理器，当github官网主页卡顿时的替代品，通过token实现帐户识别。
