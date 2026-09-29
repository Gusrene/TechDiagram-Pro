<<<<<<< HEAD
<!DOCTYPE html>
<html lang="es" class="h-full">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TechDiagram Pro - Seguridad, Redes, BESS, IoT y Fotovoltaico</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            mono: ['JetBrains Mono', 'monospace'],
          },
          colors: {
            brand: {
              50: '#eef2ff',
              100: '#e0e7ff',
              500: '#6366f1',
              600: '#4f46e5',
              700: '#4338ca',
              900: '#1e1b4b',
            }
          }
        }
      }
    }
  </script>
  <style>
    body {
      font-family: 'Inter', sans-serif;
      user-select: none;
    }
    .grid-bg {
      background-size: 24px 24px;
      background-image: 
        linear-gradient(to right, rgba(148, 163, 184, 0.12) 1px, transparent 1px),
        linear-gradient(to bottom, rgba(148, 163, 184, 0.12) 1px, transparent 1px);
    }
    .dark .grid-bg {
      background-image: 
        linear-gradient(to right, rgba(51, 65, 85, 0.4) 1px, transparent 1px),
        linear-gradient(to bottom, rgba(51, 65, 85, 0.4) 1px, transparent 1px);
    }
    .connector-line {
      stroke-linecap: round;
      transition: stroke-width 0.15s ease;
    }
    .connector-line:hover {
      stroke-width: 4.5px !important;
      cursor: pointer;
    }
    .pathway-line {
      cursor: pointer;
      transition: opacity 0.15s;
    }
    .pathway-line:hover {
      opacity: 0.85;
    }
    .node-card {
      transition: box-shadow 0.15s ease, transform 0.05s ease;
    }
    .node-card.selected {
      outline: 2.5px solid #6366f1;
      outline-offset: 2px;
    }
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: transparent;
    }
    ::-webkit-scrollbar-thumb {
      background: #94a3b8;
      border-radius: 4px;
    }
    .dark ::-webkit-scrollbar-thumb {
      background: #475569;
    }
  </style>
</head>
<body class="h-full bg-slate-900 text-slate-100 flex flex-col overflow-hidden">

  <!-- Header / Barra Superior -->
  <header class="h-14 border-b border-slate-800 bg-slate-950/80 backdrop-blur px-4 flex items-center justify-between shrink-0 z-20">
    <div class="flex items-center space-x-3">
      <div class="w-8 h-8 rounded-lg bg-gradient-to-tr from-amber-500 via-indigo-500 to-sky-400 flex items-center justify-center shadow-lg shadow-amber-500/20 font-bold text-white text-base">
        ☀️
      </div>
      <div>
        <h1 class="text-sm font-semibold tracking-wide flex items-center gap-2">
          TechDiagram Pro
          <span class="text-[10px] uppercase font-mono px-1.5 py-0.5 rounded bg-amber-500/20 text-amber-300 border border-amber-500/30">CCTV • Redes • Solar PV • BESS • IoT</span>
        </h1>
        <p class="text-[11px] text-slate-400">Diagramador de Sistemas Especializados, Energía Solar y Canalizaciones</p>
      </div>
    </div>

    <!-- Barra de Herramientas Central -->
    <div class="flex items-center gap-1.5 bg-slate-900/90 border border-slate-800 p-1 rounded-xl shadow-inner">
      <button id="toolSelect" onclick="setInteractionMode('select')" title="Seleccionar y Mover (V)" class="p-1.5 px-3 rounded-lg text-xs font-medium flex items-center gap-1.5 bg-indigo-600 text-white transition">
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122"/></svg>
        <span>Mover</span>
      </button>

      <button id="toolConnect" onclick="setInteractionMode('connect')" title="Conectar Dispositivos / Cables (C)" class="p-1.5 px-3 rounded-lg text-xs font-medium flex items-center gap-1.5 text-slate-300 hover:bg-slate-800 transition">
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1"/></svg>
        <span>Cablear</span>
      </button>

      <button id="toolPathway" onclick="setInteractionMode('pathway')" title="Trazar Canalización / Tubería / Escalerilla (P)" class="p-1.5 px-3 rounded-lg text-xs font-medium flex items-center gap-1.5 text-slate-300 hover:bg-slate-800 transition">
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"/></svg>
        <span>Canalización</span>
      </button>

      <div class="h-4 w-px bg-slate-800 mx-1"></div>

      <!-- Selector de Tipo de Cable o Canalización -->
      <div class="flex items-center gap-1.5 text-xs text-slate-300 pl-1">
        <span class="text-[11px] text-slate-400" id="toolTypeLabel">Medio:</span>
        <select id="cableTypeSelect" class="bg-slate-800 border border-slate-700 rounded-lg px-2 py-1 text-xs focus:ring-1 focus:ring-indigo-500 outline-none text-slate-200">
          <optgroup label="Cables Solares & Potencia (NEC 690)">
            <option value="pv_dc">Solar DC 1500V H1Z2Z2-K (6mm²)</option>
            <option value="pv_ground">Tierra Solar / Bajante (16mm²)</option>
            <option value="ac_power">AC 120/240V/480V (Potencia)</option>
          </optgroup>
          <optgroup label="Cables de Red y Telecomunicaciones">
            <option value="poe">Cat6 / PoE+ (Red IP)</option>
            <option value="fiber">Fibra Óptica OM3/OS2 (Troncal)</option>
            <option value="wiegand">Wiegand / RS-485 Blindado</option>
            <option value="wireless">Inalámbrico / Wi-Fi / LoRa</option>
          </optgroup>
          <optgroup label="Canalizaciones (Norma TIA-569 / NEC)">
            <option value="conduit_emt_34">Tubería EMT 3/4" (Metálica)</option>
            <option value="conduit_emt_1">Tubería EMT 1" (Troncal)</option>
            <option value="conduit_pvc_1">Tubería PVC Pesado 1" (Subterráneo)</option>
            <option value="tray_mesh_150">Escalerilla Malla 150mm</option>
            <option value="tray_ladder_300">Escalerilla Tipo Escalera 300mm</option>
          </optgroup>
        </select>
      </div>

      <div class="h-4 w-px bg-slate-800 mx-1"></div>

      <!-- Gestión de Plano de Fondo y Escala -->
      <label class="p-1.5 px-2.5 rounded-lg text-xs font-medium flex items-center gap-1 bg-slate-800 hover:bg-slate-700 text-slate-200 cursor-pointer transition" title="Subir plano de arquitectura (JPG, PNG, SVG)">
        <span>📐 Subir Plano</span>
        <input type="file" id="floorPlanInput" accept="image/*" class="hidden" onchange="handleFloorPlanUpload(event)">
      </label>

      <button id="btnCalibrateScale" onclick="startScaleCalibration()" class="p-1.5 px-2 rounded-lg text-xs font-medium text-amber-300 bg-amber-500/10 hover:bg-amber-500/20 border border-amber-500/30 transition flex items-center gap-1" title="Calibrar Escala (clic en 2 puntos con distancia conocida)">
        <span>📏</span>
        <span id="scaleLabelText">1m = 20px</span>
      </button>

      <div class="h-4 w-px bg-slate-800 mx-1"></div>

      <!-- Asistente de Cálculo Solar Rápido -->
      <button onclick="openPvCalculatorModal()" class="p-1.5 px-2.5 rounded-lg text-xs font-semibold bg-amber-500/20 hover:bg-amber-500/30 text-amber-300 border border-amber-500/40 flex items-center gap-1.5 transition" title="Cálculos Fotovoltaicos (Voc máx, MPPT, Corrientes NEC 690 y Generación)">
        <span>⚡</span>
        <span>Cálculo Solar</span>
      </button>

      <div class="h-4 w-px bg-slate-800 mx-1"></div>

      <!-- Controles Zoom y Rejilla -->
      <button onclick="zoomCanvas(0.1)" title="Zoom +" class="p-1.5 hover:bg-slate-800 rounded text-slate-400 hover:text-white transition">
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4"/></svg>
      </button>
      <span id="zoomLevelText" class="text-[11px] font-mono text-slate-400 w-10 text-center">100%</span>
      <button onclick="zoomCanvas(-0.1)" title="Zoom -" class="p-1.5 hover:bg-slate-800 rounded text-slate-400 hover:text-white transition">
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 12H4"/></svg>
      </button>
      <button onclick="resetZoom()" title="Restablecer Vista" class="p-1.5 hover:bg-slate-800 rounded text-slate-400 hover:text-white transition text-xs font-mono">
        1:1
      </button>
      <button id="gridToggleBtn" onclick="toggleGrid()" title="Activar/Desactivar Rejilla" class="p-1.5 hover:bg-slate-800 rounded text-indigo-400 transition text-xs font-mono px-2">
        # Snap
      </button>
    </div>

    <!-- Botones de Acción (Plantillas, BOM, Exportar) -->
    <div class="flex items-center gap-2">
      <!-- Selector de Plantilla -->
      <div class="relative">
        <button onclick="toggleDropdown('templatesDropdown')" class="px-2.5 py-1.5 text-xs font-medium bg-slate-800 hover:bg-slate-700 border border-slate-700 rounded-lg flex items-center gap-1.5 transition">
          <span>Plantillas</span>
          <svg class="w-3 h-3 text-slate-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div id="templatesDropdown" class="hidden absolute right-0 mt-2 w-72 bg-slate-900 border border-slate-800 rounded-xl shadow-2xl p-1.5 z-50 text-xs">
          <div class="text-[10px] text-slate-400 uppercase font-semibold px-2 py-1">Plantillas de Ingeniería</div>
          <button onclick="loadTemplate('pv_commercial'); toggleDropdown('templatesDropdown')" class="w-full text-left px-2.5 py-2 hover:bg-slate-800 rounded-lg flex flex-col gap-0.5">
            <span class="font-medium text-amber-300">☀️ Planta Solar Comercial (15 kWp + Inversor)</span>
            <span class="text-[10px] text-slate-400">Strings en serie, Combiner Box, DPS y Medidor</span>
          </button>
          <button onclick="loadTemplate('bess_pv'); toggleDropdown('templatesDropdown')" class="w-full text-left px-2.5 py-2 hover:bg-slate-800 rounded-lg flex flex-col gap-0.5">
            <span class="font-medium text-emerald-300">🔋 Fotovoltaico Híbrido con BESS (Respaldo)</span>
            <span class="text-[10px] text-slate-400">Paneles PV, Inversor Híbrido, Baterías LiFePO4</span>
          </button>
          <button onclick="loadTemplate('cctv_acs'); toggleDropdown('templatesDropdown')" class="w-full text-left px-2.5 py-2 hover:bg-slate-800 rounded-lg flex flex-col gap-0.5">
            <span class="font-medium text-sky-300">📹 CCTV & Control de Acceso</span>
            <span class="text-[10px] text-slate-400">NVR, Cámaras PoE, Lectoras y Maglock</span>
          </button>
          <button onclick="loadTemplate('iot_net'); toggleDropdown('templatesDropdown')" class="w-full text-left px-2.5 py-2 hover:bg-slate-800 rounded-lg flex flex-col gap-0.5">
            <span class="font-medium text-indigo-300">🌐 Red IT & Puerta de Enlace IoT</span>
            <span class="text-[10px] text-slate-400">Core Switch, APs, Gateways y Sensores</span>
          </button>
        </div>
      </div>

      <!-- Botón Cómputo de Materiales (BOM) -->
      <button onclick="openBomModal()" class="px-2.5 py-1.5 text-xs font-medium bg-emerald-600/20 text-emerald-300 border border-emerald-500/30 hover:bg-emerald-600/30 rounded-lg flex items-center gap-1.5 transition">
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01"/></svg>
        <span>Listado Materiales (BOM)</span>
      </button>

      <!-- Botón Exportar -->
      <div class="relative">
        <button onclick="toggleDropdown('exportDropdown')" class="px-3 py-1.5 text-xs font-semibold bg-indigo-600 hover:bg-indigo-500 rounded-lg flex items-center gap-1.5 shadow-md shadow-indigo-600/20 transition">
          <span>Exportar / Guardar</span>
          <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
        </button>
        <div id="exportDropdown" class="hidden absolute right-0 mt-2 w-48 bg-slate-900 border border-slate-800 rounded-xl shadow-2xl p-1 z-50 text-xs">
          <button onclick="exportProjectJSON(); toggleDropdown('exportDropdown')" class="w-full text-left px-3 py-2 hover:bg-slate-800 rounded-lg flex items-center gap-2">
            <span>💾</span> Guardar Proyecto (JSON)
          </button>
          <label class="w-full text-left px-3 py-2 hover:bg-slate-800 rounded-lg flex items-center gap-2 cursor-pointer">
            <span>📂</span> Abrir Proyecto (JSON)
            <input type="file" id="importJsonInput" accept=".json" class="hidden" onchange="importProjectJSON(event)">
          </label>
          <div class="h-px bg-slate-800 my-1"></div>
          <button onclick="exportDiagramSVG(); toggleDropdown('exportDropdown')" class="w-full text-left px-3 py-2 hover:bg-slate-800 rounded-lg flex items-center gap-2">
            <span>📐</span> Exportar Imagen SVG
          </button>
          <button onclick="clearCanvas(); toggleDropdown('exportDropdown')" class="w-full text-left px-3 py-2 hover:bg-red-500/20 text-red-400 rounded-lg flex items-center gap-2">
            <span>🗑️</span> Limpiar Lienzo
          </button>
        </div>
      </div>
    </div>
  </header>

  <!-- Contenedor Principal: Biblioteca Lateral + Canvas + Inspector -->
  <div class="flex-1 flex overflow-hidden relative">

    <!-- BARRA LATERAL IZQUIERDA: PALETA DE COMPONENTES -->
    <aside class="w-80 bg-slate-950 border-r border-slate-800 flex flex-col shrink-0 z-10">
      <div class="p-3 border-b border-slate-800">
        <div class="relative">
          <input type="text" id="searchComponent" onkeyup="filterComponents()" placeholder="Buscar equipo (panel, inversor, CCTV, switch...)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2.5 py-1.5 pl-8 text-xs text-slate-200 placeholder-slate-500 focus:outline-none focus:border-indigo-500">
          <svg class="w-3.5 h-3.5 text-slate-500 absolute left-2.5 top-2.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
        </div>
      </div>

      <!-- Categorías de Dispositivos Acordeón -->
      <div class="flex-1 overflow-y-auto p-2 space-y-3" id="componentLibraryList">

        <!-- 1. ENERGÍA SOLAR FOTOVOLTAICA (COMPLETA Y ESPECIALIZADA) -->
        <div class="category-block">
          <div class="flex items-center justify-between text-[11px] font-bold text-amber-400 uppercase tracking-wider px-2 py-1 bg-amber-950/40 rounded border border-amber-900/40">
            <span>☀️ Fotovoltaico & Paneles Solares</span>
            <span class="text-[9px] bg-amber-900/60 px-1 rounded text-amber-200">DC / MPPT</span>
          </div>
          <div class="grid grid-cols-2 gap-1.5 mt-1.5">
            <button onclick="addNodeToCanvas('pv_module_580')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-amber-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🪟</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Panel Solar 580W</span>
              <span class="text-[9px] text-amber-400 font-mono">TOPCon Bifacial</span>
            </button>
            <button onclick="addNodeToCanvas('pv_string')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-amber-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">☀️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">String Solar (10 Mod)</span>
              <span class="text-[9px] text-amber-400 font-mono">5.8 kWp • 500V DC</span>
            </button>
            <button onclick="addNodeToCanvas('pv_inverter_string')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-amber-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">⚡</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Inversor String On-Grid</span>
              <span class="text-[9px] text-amber-400 font-mono">10kW • Dual MPPT</span>
            </button>
            <button onclick="addNodeToCanvas('pv_inverter')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-amber-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🔄</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Inversor Híbrido BESS</span>
              <span class="text-[9px] text-amber-400 font-mono">6kW MPPT/Batería</span>
            </button>
            <button onclick="addNodeToCanvas('pv_microinverter')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-amber-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🔲</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Microinversor 4-en-1</span>
              <span class="text-[9px] text-amber-400 font-mono">2000W AC • Rapid Off</span>
            </button>
            <button onclick="addNodeToCanvas('pv_combiner_box')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-amber-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🧰</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Combiner Box DC 4-in</span>
              <span class="text-[9px] text-amber-400 font-mono">Fusibles gPV + DPS</span>
            </button>
            <button onclick="addNodeToCanvas('pv_dc_disconnect')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-amber-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🛑</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Seccionador DC 1000V</span>
              <span class="text-[9px] text-amber-400 font-mono">Corte Carga 32A</span>
            </button>
            <button onclick="addNodeToCanvas('pv_spd_ground')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-amber-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">⚡</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Supresor DPS & Tierra</span>
              <span class="text-[9px] text-amber-400 font-mono">Tipo II 1000V DC</span>
            </button>
          </div>
        </div>

        <!-- 2. ALMACENAMIENTO BESS & TABLEROS ELÉCTRICOS -->
        <div class="category-block">
          <div class="flex items-center justify-between text-[11px] font-bold text-emerald-400 uppercase tracking-wider px-2 py-1 bg-emerald-950/30 rounded border border-emerald-900/30">
            <span>🔋 Almacenamiento BESS & Tableros</span>
            <span class="text-[9px] bg-emerald-900/50 px-1 rounded text-emerald-300">LiFePO4 / AC</span>
          </div>
          <div class="grid grid-cols-2 gap-1.5 mt-1.5">
            <button onclick="addNodeToCanvas('bess_battery')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-emerald-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🔋</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">BESS Rack LiFePO4</span>
              <span class="text-[9px] text-emerald-400 font-mono">5.12 kWh / 48V</span>
            </button>
            <button onclick="addNodeToCanvas('bess_commercial_cabinet')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-emerald-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🗄️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Gabinete BESS 30kWh</span>
              <span class="text-[9px] text-emerald-400 font-mono">Industrial HV / BMS</span>
            </button>
            <button onclick="addNodeToCanvas('elec_panel')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-emerald-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🔌</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Tablero AC / ATS</span>
              <span class="text-[9px] text-slate-400 font-mono">120/240V Cargas</span>
            </button>
            <button onclick="addNodeToCanvas('iot_smart_meter')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-emerald-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">📊</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Medidor Bidireccional</span>
              <span class="text-[9px] text-purple-400 font-mono">Zero Export / RS-485</span>
            </button>
          </div>
        </div>

        <!-- 3. CCTV & SEGURIDAD ELECTRÓNICA -->
        <div class="category-block">
          <div class="flex items-center justify-between text-[11px] font-bold text-sky-400 uppercase tracking-wider px-2 py-1 bg-sky-950/30 rounded border border-sky-900/30">
            <span>📹 CCTV & Videovigilancia</span>
            <span class="text-[9px] bg-sky-900/50 px-1 rounded text-sky-300">PoE / IP</span>
          </div>
          <div class="grid grid-cols-2 gap-1.5 mt-1.5">
            <button onclick="addNodeToCanvas('cam_dome')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-sky-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🎥</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Cámara Domo IP</span>
              <span class="text-[9px] text-slate-400 font-mono">7W PoE</span>
            </button>
            <button onclick="addNodeToCanvas('cam_bullet')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-sky-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">📹</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Cámara Bullet 4K</span>
              <span class="text-[9px] text-slate-400 font-mono">9W PoE</span>
            </button>
            <button onclick="addNodeToCanvas('cam_ptz')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-sky-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🛰️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Cámara PTZ 360°</span>
              <span class="text-[9px] text-slate-400 font-mono">25W Hi-PoE</span>
            </button>
            <button onclick="addNodeToCanvas('nvr_server')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-sky-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🗄️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">NVR / VMS 32Ch</span>
              <span class="text-[9px] text-slate-400 font-mono">110V/220V AC</span>
            </button>
          </div>
        </div>

        <!-- 4. CONTROL DE ACCESO -->
        <div class="category-block">
          <div class="flex items-center justify-between text-[11px] font-bold text-teal-400 uppercase tracking-wider px-2 py-1 bg-teal-950/30 rounded border border-teal-900/30">
            <span>🚪 Control de Acceso</span>
            <span class="text-[9px] bg-teal-900/50 px-1 rounded text-teal-300">Wiegand/IP</span>
          </div>
          <div class="grid grid-cols-2 gap-1.5 mt-1.5">
            <button onclick="addNodeToCanvas('acs_panel')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-teal-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🎛️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Panel Acceso 4P</span>
              <span class="text-[9px] text-slate-400 font-mono">12V DC / Red</span>
            </button>
            <button onclick="addNodeToCanvas('acs_reader')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-teal-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">💳</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Lectora RFID/Bio</span>
              <span class="text-[9px] text-slate-400 font-mono">Wiegand/OSDP</span>
            </button>
            <button onclick="addNodeToCanvas('acs_maglock')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-teal-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🧲</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Electroimán 600lb</span>
              <span class="text-[9px] text-slate-400 font-mono">12V 500mA</span>
            </button>
            <button onclick="addNodeToCanvas('acs_rex')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-teal-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🔘</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Botón REX Salida</span>
              <span class="text-[9px] text-slate-400 font-mono">Contacto Seco</span>
            </button>
          </div>
        </div>

        <!-- 5. REDES & TELECOMUNICACIONES -->
        <div class="category-block">
          <div class="flex items-center justify-between text-[11px] font-bold text-indigo-400 uppercase tracking-wider px-2 py-1 bg-indigo-950/30 rounded border border-indigo-900/30">
            <span>🌐 Redes & Telecom</span>
            <span class="text-[9px] bg-indigo-900/50 px-1 rounded text-indigo-300">Gigabit / PoE</span>
          </div>
          <div class="grid grid-cols-2 gap-1.5 mt-1.5">
            <button onclick="addNodeToCanvas('net_switch_poe')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-indigo-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🔀</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Switch 24P PoE+</span>
              <span class="text-[9px] text-indigo-400 font-mono">Budget 370W</span>
            </button>
            <button onclick="addNodeToCanvas('net_router')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-indigo-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🛡️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Router Firewall</span>
              <span class="text-[9px] text-slate-400 font-mono">Dual-WAN</span>
            </button>
            <button onclick="addNodeToCanvas('net_ap')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-indigo-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">📶</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Access Point Wi-Fi 6</span>
              <span class="text-[9px] text-slate-400 font-mono">13W PoE</span>
            </button>
            <button onclick="addNodeToCanvas('net_rack')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-indigo-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🚪</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Gabinete Rack 24U</span>
              <span class="text-[9px] text-slate-400 font-mono">Estructura IT</span>
            </button>
          </div>
        </div>

        <!-- 6. IOT & SENSORES -->
        <div class="category-block">
          <div class="flex items-center justify-between text-[11px] font-bold text-purple-400 uppercase tracking-wider px-2 py-1 bg-purple-950/30 rounded border border-purple-900/30">
            <span>📡 IoT & Sensores</span>
            <span class="text-[9px] bg-purple-900/50 px-1 rounded text-purple-300">LoRa/MQTT</span>
          </div>
          <div class="grid grid-cols-2 gap-1.5 mt-1.5">
            <button onclick="addNodeToCanvas('iot_gateway')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-purple-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🛰️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Gateway LoRaWAN</span>
              <span class="text-[9px] text-slate-400 font-mono">PoE / 915MHz</span>
            </button>
            <button onclick="addNodeToCanvas('iot_sensor')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-purple-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🌡️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Sensor Temp/Hum</span>
              <span class="text-[9px] text-slate-400 font-mono">Batería Li-Ion</span>
            </button>
            <button onclick="addNodeToCanvas('iot_plc')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-purple-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">⚙️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">PLC Industrial IoT</span>
              <span class="text-[9px] text-slate-400 font-mono">24V DC / Modbus</span>
            </button>
          </div>
        </div>

        <!-- 7. CANALIZACIONES Y CAJAS (TIA-569 / NEC) -->
        <div class="category-block">
          <div class="flex items-center justify-between text-[11px] font-bold text-cyan-400 uppercase tracking-wider px-2 py-1 bg-cyan-950/30 rounded border border-cyan-900/30">
            <span>🏗️ Cajas & Pasos de Canalización</span>
            <span class="text-[9px] bg-cyan-900/50 px-1 rounded text-cyan-300">Norma TIA-569</span>
          </div>
          <div class="grid grid-cols-2 gap-1.5 mt-1.5">
            <button onclick="addNodeToCanvas('box_junction_4x4')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-cyan-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">📦</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Caja Paso 4"x4"</span>
              <span class="text-[9px] text-slate-400 font-mono">Con Tapa Ciega</span>
            </button>
            <button onclick="addNodeToCanvas('box_pull_nema')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-cyan-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🗃️</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Registro NEMA 12x12"</span>
              <span class="text-[9px] text-slate-400 font-mono">Caja de Halado</span>
            </button>
            <button onclick="addNodeToCanvas('condulet_tee')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-cyan-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🪜</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Condulet Tipo T / LB</span>
              <span class="text-[9px] text-slate-400 font-mono">Aluminio 3/4"</span>
            </button>
            <button onclick="addNodeToCanvas('box_chalupa')" class="comp-btn flex flex-col items-center justify-center p-2 rounded-lg bg-slate-900 hover:bg-slate-800 border border-slate-800 hover:border-cyan-500/50 transition group">
              <span class="text-xl mb-1 group-hover:scale-110 transition">🔲</span>
              <span class="text-[11px] font-medium text-slate-300 text-center">Caja 2x4" (Chalupa)</span>
              <span class="text-[9px] text-slate-400 font-mono">Para Placa/Faceplate</span>
            </button>
          </div>
        </div>

      </div>

      <!-- Métricas y Resumen en Vivo -->
      <div class="p-3 border-t border-slate-800 bg-slate-900/60 text-[11px] space-y-1.5">
        <div class="text-[10px] text-slate-400 font-semibold uppercase flex items-center justify-between">
          <span>Balance & Metrado</span>
          <span class="text-amber-400 flex items-center gap-1">⚡ Sistema Híbrido</span>
        </div>
        <div class="flex justify-between items-center text-slate-300">
          <span class="flex items-center gap-1.5"><span class="w-2 h-2 rounded-full bg-amber-400"></span>Potencia Solar Pico:</span>
          <span id="metricPvTotal" class="font-mono font-semibold text-amber-400">0 kWp</span>
        </div>
        <div class="flex justify-between items-center text-slate-300">
          <span class="flex items-center gap-1.5"><span class="w-2 h-2 rounded-full bg-amber-300"></span>Generación Estimada:</span>
          <span id="metricPvDaily" class="font-mono font-semibold text-amber-300">0 kWh/día</span>
        </div>
        <div class="flex justify-between items-center text-slate-300">
          <span class="flex items-center gap-1.5"><span class="w-2 h-2 rounded-full bg-emerald-400"></span>Capacidad BESS:</span>
          <span id="metricBessTotal" class="font-mono font-semibold text-emerald-400">0 kWh</span>
        </div>
        <div class="flex justify-between items-center text-slate-300">
          <span class="flex items-center gap-1.5"><span class="w-2 h-2 rounded-full bg-sky-400"></span>Consumo PoE IT:</span>
          <span id="metricPoeTotal" class="font-mono font-semibold text-sky-400">0 W</span>
        </div>
        <div class="flex justify-between items-center text-slate-300 pt-1 border-t border-slate-800/80">
          <span class="flex items-center gap-1.5"><span class="w-2 h-2 rounded-full bg-cyan-400"></span>Canalizaciones:</span>
          <span id="metricPathwaysTotal" class="font-mono font-semibold text-cyan-400">0 m</span>
        </div>
      </div>
    </aside>

    <!-- ÁREA CENTRAL: LIENZO (CANVAS DE DIBUJO) -->
    <main class="flex-1 relative overflow-hidden bg-slate-900 grid-bg" id="canvasContainer">

      <!-- Contenedor transformable (Paneo y Zoom) -->
      <div id="canvasViewport" class="absolute inset-0 origin-top-left" style="transform: translate(0px, 0px) scale(1);">

        <!-- Imagen de Plano de Fondo (Subido por el usuario) -->
        <div id="floorPlanWrapper" class="absolute left-0 top-0 pointer-events-none select-none z-0 hidden">
          <img id="floorPlanImg" class="max-w-none opacity-40" alt="Plano Arquitectónico">
        </div>

        <!-- SVG de Conexiones de Cables y Canalizaciones -->
        <svg id="connectionsSvg" class="absolute inset-0 w-[5000px] h-[5000px] pointer-events-none z-0">
          <defs>
            <!-- Marcadores de Flechas y Extremos -->
            <marker id="arrow-poe" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto">
              <path d="M0,0 L0,6 L6,3 z" fill="#38bdf8"/>
            </marker>
            <marker id="arrow-pv" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto">
              <path d="M0,0 L0,6 L6,3 z" fill="#f59e0b"/>
            </marker>
            <marker id="arrow-pv-ground" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto">
              <path d="M0,0 L0,6 L6,3 z" fill="#84cc16"/>
            </marker>
            <marker id="arrow-ac" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto">
              <path d="M0,0 L0,6 L6,3 z" fill="#ef4444"/>
            </marker>
            <marker id="arrow-wiegand" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto">
              <path d="M0,0 L0,6 L6,3 z" fill="#10b981"/>
            </marker>
            <marker id="arrow-fiber" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto">
              <path d="M0,0 L0,6 L6,3 z" fill="#ec4899"/>
            </marker>
            <!-- Patrón de Escalerilla / Bandeja Portacables -->
            <pattern id="trayPattern" width="16" height="16" patternUnits="userSpaceOnUse">
              <line x1="0" y1="0" x2="16" y2="0" stroke="#0891b2" stroke-width="2"/>
              <line x1="0" y1="16" x2="16" y2="16" stroke="#0891b2" stroke-width="2"/>
              <line x1="8" y1="0" x2="8" y2="16" stroke="#22d3ee" stroke-width="2"/>
            </pattern>
          </defs>

          <!-- Capa de Canalizaciones (Tuberías y Escalerillas) -->
          <g id="pathwaysLayer"></g>

          <!-- Capa de Cables y Conexiones Eléctricas/Datos -->
          <g id="connectionsLayer"></g>

          <!-- Línea fantasma temporal durante el trazado -->
          <line id="tempCableLine" x1="0" y1="0" x2="0" y2="0" stroke="#6366f1" stroke-width="2.5" stroke-dasharray="4,4" class="hidden"/>
          <!-- Línea de calibración -->
          <line id="calibrationLine" x1="0" y1="0" x2="0" y2="0" stroke="#f59e0b" stroke-width="3" stroke-dasharray="6,4" class="hidden"/>
        </svg>

        <!-- Capa de Nodos / Equipos -->
        <div id="nodesLayer" class="absolute inset-0 w-[5000px] h-[5000px] z-10 pointer-events-auto"></div>

      </div>

      <!-- Barra flotante de Controles de Plano (Visible si hay plano cargado) -->
      <div id="planControlBar" class="hidden absolute top-4 left-4 bg-slate-950/90 backdrop-blur border border-slate-800 rounded-xl p-2 flex items-center gap-3 text-xs z-20 text-slate-300 shadow-xl">
        <span class="font-medium text-slate-200 flex items-center gap-1.5">
          <span>📐</span> Plano Activo
        </span>
        <div class="flex items-center gap-1.5 text-[11px] text-slate-400">
          <span>Opacidad:</span>
          <input type="range" id="planOpacityRange" min="5" max="100" value="40" oninput="changePlanOpacity(this.value)" class="w-20 accent-indigo-500 cursor-pointer">
        </div>
        <button onclick="togglePlanVisibility()" class="px-2 py-0.5 rounded bg-slate-800 hover:bg-slate-700 text-slate-300 text-[10px]">
          Ocultar/Ver
        </button>
        <button onclick="removeFloorPlan()" class="px-2 py-0.5 rounded bg-red-500/20 hover:bg-red-500/30 text-red-300 text-[10px]">
          Quitar
        </button>
      </div>

      <!-- Indicador de modo en la esquina inferior izquierda -->
      <div class="absolute bottom-4 left-4 bg-slate-950/80 backdrop-blur border border-slate-800 rounded-lg px-3 py-1.5 flex items-center gap-2 text-xs z-10 text-slate-300">
        <span id="modeStatusDot" class="w-2.5 h-2.5 rounded-full bg-indigo-500 animate-pulse"></span>
        <span id="modeStatusText">Modo: Mover y Seleccionar</span>
        <span class="text-slate-500 text-[10px] pl-2 border-l border-slate-800">Usa Clic Izq para mover nodos o conectar</span>
      </div>

    </main>

    <!-- BARRA LATERAL DERECHA: INSPECTOR DE PROPIEDADES -->
    <aside id="inspectorPanel" class="w-84 bg-slate-950 border-l border-slate-800 flex flex-col shrink-0 z-10">
      <div class="p-3.5 border-b border-slate-800 flex items-center justify-between">
        <div class="flex items-center gap-2">
          <span class="text-base" id="inspIcon">⚙️</span>
          <div>
            <h2 class="text-xs font-semibold text-slate-100" id="inspTitle">Propiedades</h2>
            <p class="text-[10px] text-slate-400" id="inspSubtitle">Selecciona un equipo o cable</p>
          </div>
        </div>
        <button id="deleteSelectedBtn" onclick="deleteSelected()" title="Eliminar seleccionado (Supr / Del)" class="p-1.5 rounded-lg bg-red-500/10 hover:bg-red-500/20 text-red-400 transition hidden">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"/></svg>
        </button>
      </div>

      <!-- Contenido del Inspector (Formulario Dinámico) -->
      <div class="flex-1 overflow-y-auto p-4 space-y-4 text-xs" id="inspectorBody">
        <div class="text-center py-12 text-slate-500">
          <svg class="w-10 h-10 mx-auto mb-2 text-slate-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122"/></svg>
          <p class="font-medium text-slate-400">Sin Selección</p>
          <p class="text-[11px] mt-1 max-w-[200px] mx-auto">Haz clic en cualquier panel solar, inversor, switch o tubería para configurar sus parámetros.</p>
        </div>
      </div>

      <!-- Pie de página con atajos -->
      <div class="p-3 border-t border-slate-800 bg-slate-900/40 text-[10px] text-slate-400 flex flex-col gap-1 font-mono">
        <div class="flex justify-between"><span>[V]</span> <span>Modo Seleccionar</span></div>
        <div class="flex justify-between"><span>[C]</span> <span>Modo Cablear</span></div>
        <div class="flex justify-between"><span>[P]</span> <span>Modo Canalización</span></div>
        <div class="flex justify-between"><span>[Supr]</span> <span>Borrar Elemento</span></div>
      </div>
    </aside>

  </div>

  <!-- MODAL: ASISTENTE DE CÁLCULO SOLAR FOTOVOLTAICO (NEC 690 / IEC 62548) -->
  <div id="pvCalculatorModal" class="hidden fixed inset-0 z-50 bg-black/70 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="bg-slate-900 border border-slate-800 w-full max-w-2xl rounded-2xl shadow-2xl overflow-hidden flex flex-col">
      <div class="p-4 border-b border-slate-800 flex items-center justify-between bg-slate-950">
        <div class="flex items-center gap-2.5">
          <div class="p-2 rounded-lg bg-amber-500/20 text-amber-400 text-lg">☀️</div>
          <div>
            <h3 class="font-bold text-slate-100 text-sm">Asistente de Ingeniería Fotovoltaica (NEC 690)</h3>
            <p class="text-xs text-slate-400">Dimensionamiento de strings, tensión Voc máx corregida y verificación MPPT</p>
          </div>
        </div>
        <button onclick="closePvCalculatorModal()" class="text-slate-400 hover:text-white p-1 rounded-lg hover:bg-slate-800 transition">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>

      <div class="p-5 space-y-4 text-xs text-slate-300 overflow-y-auto max-h-[75vh]">
        <div class="grid grid-cols-3 gap-3 bg-slate-950/60 p-3 rounded-xl border border-slate-800">
          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Módulos por String</label>
            <input type="number" id="calcPvModulesCount" value="12" min="1" max="30" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-2.5 py-1.5 text-xs text-amber-300 font-mono" oninput="runPvCalculations()">
          </div>
          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Potencia Módulo (Wp)</label>
            <input type="number" id="calcPvModuleWp" value="580" min="50" max="800" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-2.5 py-1.5 text-xs text-amber-300 font-mono" oninput="runPvCalculations()">
          </div>
          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Voc STC (V)</label>
            <input type="number" id="calcPvVoc" value="51.2" step="0.1" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-2.5 py-1.5 text-xs text-slate-200 font-mono" oninput="runPvCalculations()">
          </div>
          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Vmp STC (V)</label>
            <input type="number" id="calcPvVmp" value="43.1" step="0.1" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-2.5 py-1.5 text-xs text-slate-200 font-mono" oninput="runPvCalculations()">
          </div>
          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Isc STC (A)</label>
            <input type="number" id="calcPvIsc" value="14.2" step="0.1" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-2.5 py-1.5 text-xs text-slate-200 font-mono" oninput="runPvCalculations()">
          </div>
          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Temp. Mínima Sitio (°C)</label>
            <input type="number" id="calcPvTmin" value="0" step="1" class="w-full bg-slate-900 border border-slate-700 rounded-lg px-2.5 py-1.5 text-xs text-sky-300 font-mono" oninput="runPvCalculations()">
          </div>
        </div>

        <!-- Resultados del Cálculo Solar -->
        <div class="grid grid-cols-2 gap-3">
          <div class="p-3 rounded-xl bg-slate-950 border border-slate-800 space-y-1.5">
            <div class="text-[11px] font-bold text-amber-400 uppercase">Tensión Máxima Corregida (NEC 690.7)</div>
            <div class="text-xl font-mono font-bold text-slate-100" id="calcResVocMax">0 V</div>
            <p class="text-[10px] text-slate-400" id="calcResVocStatus">Evaluando límite de aislamiento 1000V DC / 1500V DC...</p>
          </div>
          <div class="p-3 rounded-xl bg-slate-950 border border-slate-800 space-y-1.5">
            <div class="text-[11px] font-bold text-sky-400 uppercase">Tensión Operativa Vmp Nominal</div>
            <div class="text-xl font-mono font-bold text-sky-300" id="calcResVmpTotal">0 V</div>
            <p class="text-[10px] text-slate-400">Rango ideal para entrada MPPT de inversor comercial (200V - 850V).</p>
          </div>
          <div class="p-3 rounded-xl bg-slate-950 border border-slate-800 space-y-1.5">
            <div class="text-[11px] font-bold text-emerald-400 uppercase">Calibre Conductor (1.56 x Isc)</div>
            <div class="text-xl font-mono font-bold text-emerald-300" id="calcResAmpacity">0 A</div>
            <p class="text-[10px] text-slate-400" id="calcResCableSuggest">Corriente mínima de diseño según NEC 690.8.</p>
          </div>
          <div class="p-3 rounded-xl bg-slate-950 border border-slate-800 space-y-1.5">
            <div class="text-[11px] font-bold text-purple-400 uppercase">Generación Diaria Est. (5 HSP)</div>
            <div class="text-xl font-mono font-bold text-purple-300" id="calcResEnergyDaily">0 kWh/día</div>
            <p class="text-[10px] text-slate-400">Considerando PR de 80% y 5 Horas Sol Pico promedio.</p>
          </div>
        </div>

        <div class="p-3 rounded-xl bg-indigo-950/20 border border-indigo-500/30 text-[11px] text-slate-300">
          💡 <strong>Recomendación Técnica:</strong> Los cables solares deben ser certificados <strong>EN 50618 / UL 4703</strong> (H1Z2Z2-K) con doble aislamiento resistente a rayos UV. Los fusibles de protección en Combiner Box deben ser clase <strong>gPV</strong> dimensionados a $1.56 \times I_{sc}$.
        </div>
      </div>

      <div class="p-3 border-t border-slate-800 bg-slate-950 flex justify-end">
        <button onclick="closePvCalculatorModal()" class="px-4 py-1.5 bg-slate-800 hover:bg-slate-700 text-slate-200 rounded-lg text-xs font-medium transition">
          Aceptar
        </button>
      </div>
    </div>
  </div>

  <!-- MODAL: LISTA DE MATERIALES (BOM) -->
  <div id="bomModal" class="hidden fixed inset-0 z-50 bg-black/70 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="bg-slate-900 border border-slate-800 w-full max-w-4xl rounded-2xl shadow-2xl overflow-hidden flex flex-col max-h-[88vh]">
      <div class="p-4 border-b border-slate-800 flex items-center justify-between bg-slate-950">
        <div class="flex items-center gap-2.5">
          <div class="p-2 rounded-lg bg-emerald-500/20 text-emerald-400">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"/></svg>
          </div>
          <div>
            <h3 class="font-bold text-slate-100 text-sm">Cómputo & Listado de Materiales (BOM) Normativo</h3>
            <p class="text-xs text-slate-400">Equipos fotovoltaicos, CCTV, redes, cables solares/PoE, tuberías EMT y canalizaciones (TIA-569 / NEC 690)</p>
          </div>
        </div>
        <button onclick="closeBomModal()" class="text-slate-400 hover:text-white p-1 rounded-lg hover:bg-slate-800 transition">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>

      <div class="p-4 overflow-y-auto space-y-5">
        <!-- Resumen de Cumplimiento Normativo -->
        <div id="normativeAlertBox" class="p-3 rounded-xl border border-indigo-500/30 bg-indigo-950/20 flex items-start gap-3 text-xs">
          <span class="text-lg">📋</span>
          <div>
            <div class="font-bold text-indigo-300">Resumen de Cumplimiento Normativo (NEC 690, TIA-569-D & NEC 358)</div>
            <div class="text-[11px] text-slate-300 mt-0.5 space-y-0.5" id="normativeSummaryText">
              • Factor de relleno calculado bajo la regla del 40% (máximo permitido para canalizaciones de más de 2 cables).
              • Espaciamiento de soportes y abrazaderas estimado a cada 1.5 metros de tramo recto.
              • Incluye mermas reglamentarias del 10% en cableado y 5% en canalizaciones.
              • Conductores solares DC protegidos bajo sobredimensionamiento $1.56 \times I_{sc}$.
            </div>
          </div>
        </div>

        <!-- Tabla de Canalizaciones y Cajas de Paso -->
        <div>
          <h4 class="text-xs font-semibold text-cyan-400 uppercase tracking-wider mb-2 flex items-center justify-between">
            <span>Canalizaciones, Tuberías EMT, Escalerillas y Accesorios</span>
            <span id="bomPathwaysCount" class="text-cyan-400 font-mono text-xs">0 m total</span>
          </h4>
          <div class="border border-slate-800 rounded-xl overflow-hidden bg-slate-950/50">
            <table class="w-full text-left text-xs text-slate-300">
              <thead class="bg-slate-800/60 text-slate-400 uppercase font-mono text-[10px]">
                <tr>
                  <th class="p-2.5">Elemento / Tipo</th>
                  <th class="p-2.5">Medida / Especificación</th>
                  <th class="p-2.5">Metrado Neto</th>
                  <th class="p-2.5">Metrado con Merma (+5%)</th>
                  <th class="p-2.5">Accesorios Estimados (Uniones / Abrazaderas)</th>
                </tr>
              </thead>
              <tbody id="bomPathwaysTable" class="divide-y divide-slate-800/80"></tbody>
            </table>
          </div>
        </div>

        <!-- Tabla de Equipos y Cajas de Conexión -->
        <div>
          <h4 class="text-xs font-semibold text-slate-300 uppercase tracking-wider mb-2 flex items-center justify-between">
            <span>Dispositivos, Equipos Solares, IT y Seguridad</span>
            <span id="bomDevicesCount" class="text-emerald-400 font-mono text-xs">0 items</span>
          </h4>
          <div class="border border-slate-800 rounded-xl overflow-hidden bg-slate-950/50">
            <table class="w-full text-left text-xs text-slate-300">
              <thead class="bg-slate-800/60 text-slate-400 uppercase font-mono text-[10px]">
                <tr>
                  <th class="p-2.5">Cant.</th>
                  <th class="p-2.5">Categoría</th>
                  <th class="p-2.5">Dispositivo / Modelo</th>
                  <th class="p-2.5">Specs / Potencia</th>
                  <th class="p-2.5">Parámetros</th>
                </tr>
              </thead>
              <tbody id="bomDevicesTable" class="divide-y divide-slate-800/80"></tbody>
            </table>
          </div>
        </div>

        <!-- Tabla de Cableado con Holgura Normativa -->
        <div>
          <h4 class="text-xs font-semibold text-slate-300 uppercase tracking-wider mb-2 flex items-center justify-between">
            <span>Cables y Conexiones Físicas (Holgura 10% TIA-568 / NEC)</span>
            <span id="bomCablesCount" class="text-sky-400 font-mono text-xs">0 enlaces</span>
          </h4>
          <div class="border border-slate-800 rounded-xl overflow-hidden bg-slate-950/50">
            <table class="w-full text-left text-xs text-slate-300">
              <thead class="bg-slate-800/60 text-slate-400 uppercase font-mono text-[10px]">
                <tr>
                  <th class="p-2.5">Tipo Cable</th>
                  <th class="p-2.5">Origen</th>
                  <th class="p-2.5">Destino</th>
                  <th class="p-2.5">Longitud Neta</th>
                  <th class="p-2.5">Total con Holgura (+10%)</th>
                  <th class="p-2.5">Etiqueta / Uso</th>
                </tr>
              </thead>
              <tbody id="bomCablesTable" class="divide-y divide-slate-800/80"></tbody>
            </table>
          </div>
        </div>
      </div>

      <div class="p-3 border-t border-slate-800 bg-slate-950 flex justify-between items-center">
        <div class="text-xs text-slate-400">
          Metrado calculado con calibración de escala real y normas TIA-569 / NEC 690.
        </div>
        <div class="flex gap-2">
          <button onclick="exportBomCSV()" class="px-3 py-1.5 bg-emerald-600 hover:bg-emerald-500 text-white rounded-lg text-xs font-medium flex items-center gap-1.5 transition">
            <span>📊</span> Exportar a Excel (CSV)
          </button>
          <button onclick="closeBomModal()" class="px-3 py-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg text-xs font-medium transition">
            Cerrar
          </button>
        </div>
      </div>
    </div>
  </div>

  <!-- MODAL: CALIBRACIÓN DE ESCALA REAL -->
  <div id="calibrationModal" class="hidden fixed inset-0 z-50 bg-black/70 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="bg-slate-900 border border-slate-800 w-full max-w-sm rounded-xl p-4 shadow-2xl">
      <h3 class="font-bold text-slate-100 text-sm mb-1 flex items-center gap-2">
        <span>📏</span> Calibrar Escala del Plano
      </h3>
      <p class="text-xs text-slate-400 mb-3">Has medido una distancia de <span id="calibratedPixelsSpan" class="text-amber-300 font-mono">0</span> píxeles en el lienzo. ¿A cuántos metros reales equivale?</p>
      
      <div class="mb-4">
        <label class="block text-[11px] font-medium text-slate-300 mb-1">Distancia Real en Metros (m):</label>
        <input type="number" id="realMetersInput" min="0.1" step="0.1" value="5.0" class="w-full bg-slate-950 border border-slate-700 rounded-lg px-3 py-2 text-sm text-slate-100 focus:outline-none focus:border-indigo-500 font-mono">
      </div>

      <div class="flex justify-end gap-2">
        <button onclick="cancelScaleCalibration()" class="px-3 py-1.5 bg-slate-800 hover:bg-slate-700 text-slate-300 rounded-lg text-xs">Cancelar</button>
        <button onclick="applyScaleCalibration()" class="px-3 py-1.5 bg-amber-600 hover:bg-amber-500 text-white rounded-lg text-xs font-semibold">Aplicar Escala</button>
      </div>
    </div>
  </div>

  <!-- Toast Notification Box -->
  <div id="toastNotification" class="fixed bottom-6 right-6 z-50 transform translate-y-20 opacity-0 transition duration-300 pointer-events-none flex items-center gap-2 px-4 py-2.5 rounded-xl bg-slate-900 border border-slate-700 text-slate-100 text-xs shadow-2xl">
    <span id="toastIcon">ℹ️</span>
    <span id="toastMessage">Acción completada</span>
  </div>

  <script>
    // --- ESTADO PRINCIPAL DE LA APLICACIÓN ---
    const APP_STATE = {
      nodes: [],
      connections: [],
      pathways: [],
      selectedNodeId: null,
      selectedConnId: null,
      selectedPathwayId: null,
      interactionMode: 'select', // 'select' | 'connect' | 'pathway' | 'calibrate'
      connectingSourceNodeId: null,
      pathwaySourceNodeId: null,
      scaleMetersPerPixel: 0.05, // 1m = 20px
      isCalibrating: false,
      calibrationPoints: [],
      floorPlanDataUrl: null,
      floorPlanVisible: true,
      floorPlanOpacity: 0.4,
      zoom: 1,
      panX: 40,
      panY: 40,
      isPanning: false,
      panStartX: 0,
      panStartY: 0,
      snapToGrid: true,
      gridSize: 24,
      isDraggingNode: false,
      draggedNodeId: null,
      dragOffsetX: 0,
      dragOffsetY: 0
    };

    // DICCIONARIO COMPLETO DE DISPOSITIVOS Y COMPONENTES
    const COMPONENT_DEFINITIONS = {
      // 1. FOTOVOLTAICO & ENERGÍA SOLAR
      pv_module_580: {
        category: 'Fotovoltaico',
        label: 'Panel Solar 580W TOPCon',
        model: 'PV-580W-BIFACIAL',
        icon: '🪟',
        badge: '580Wp DC',
        pvWp: 580,
        poeWatts: 0,
        bessKwh: 0,
        voltage: '51.2V Voc / 43.1V Vmp',
        current: '14.2A Isc / 13.5A Imp',
        ports: ['MC4 (+) 1500V', 'MC4 (-) 1500V', 'Tierra Marco'],
        color: '#d97706'
      },
      pv_string: {
        category: 'Fotovoltaico',
        label: 'String Solar 10 Módulos',
        model: 'STR-10X-580W',
        icon: '☀️',
        badge: '5.8 kWp DC',
        pvWp: 5800,
        poeWatts: 0,
        bessKwh: 0,
        voltage: '512V Voc / 431V Vmp',
        current: '14.2A Isc',
        ports: ['MC4 (+) Salida String', 'MC4 (-) Salida String', 'Conexión Equipotencial'],
        color: '#f59e0b'
      },
      pv_inverter_string: {
        category: 'Fotovoltaico',
        label: 'Inversor String On-Grid 10kW',
        model: 'INV-GRID-10K-2MPPT',
        icon: '⚡',
        badge: '10kW AC • 2 MPPT',
        pvWp: 0,
        poeWatts: 0,
        bessKwh: 0,
        voltage: '200-850V DC / 220-400V AC',
        ports: ['MPPT 1 (+) (-)', 'MPPT 2 (+) (-)', 'Salida Trifásica AC', 'RS-485 Modbus'],
        color: '#f59e0b'
      },
      pv_inverter: {
        category: 'Fotovoltaico',
        label: 'Inversor Híbrido Solar + BESS',
        model: 'INV-HYBRID-6K-48V',
        icon: '🔄',
        badge: '6kW MPPT/AC',
        pvWp: 0,
        poeWatts: 0,
        bessKwh: 0,
        voltage: '48V DC / 120-240V AC',
        ports: ['2x MPPT DC', 'Batería 48V', 'AC Red', 'AC Cargas Críticas'],
        color: '#f59e0b'
      },
      pv_microinverter: {
        category: 'Fotovoltaico',
        label: 'Microinversor 4-a-1 2000W',
        model: 'MICRO-4CH-2000W',
        icon: '🔲',
        badge: '2kW AC Quad MPPT',
        pvWp: 0,
        poeWatts: 0,
        bessKwh: 0,
        voltage: '16-60V DC / 240V AC',
        ports: ['4x Entrada MC4 DC', 'Bus AC Trunk', 'Antena ZigBee/Wi-Fi'],
        color: '#ea580c'
      },
      pv_combiner_box: {
        category: 'Fotovoltaico',
        label: 'Combiner Box DC 4 Entradas',
        model: 'CB-4IN-1OUT-1000V',
        icon: '🧰',
        badge: 'Fusibles gPV + DPS',
        pvWp: 0,
        poeWatts: 0,
        bessKwh: 0,
        voltage: '1000V DC Aislamiento',
        ports: ['4x In (+) (-)', '1x Out (+) (-)', 'Barra Tierra'],
        color: '#d97706'
      },
      pv_dc_disconnect: {
        category: 'Fotovoltaico',
        label: 'Seccionador DC 1000V 32A',
        model: 'SW-DC-1000V-32A',
        icon: '🛑',
        badge: 'Corte Bajo Carga',
        pvWp: 0,
        poeWatts: 0,
        bessKwh: 0,
        voltage: '1000V DC 32A',
        ports: ['Entrada DC', 'Salida Inversor'],
        color: '#b45309'
      },
      pv_spd_ground: {
        category: 'Fotovoltaico',
        label: 'Tablero DPS DC & Tierra Solar',
        model: 'PROT-DPS-1000V-T2',
        icon: '⚡',
        badge: 'Supresor Tipo II',
        pvWp: 0,
        poeWatts: 0,
        bessKwh: 0,
        voltage: '1000V DC / Imax 40kA',
        ports: ['Línea (+)', 'Línea (-)', 'Bajante a Tierra PE'],
        color: '#84cc16'
      },

      // 2. BESS & ENERGÍA
      bess_battery: {
        category: 'BESS',
        label: 'Batería LiFePO4 Rack 48V',
        model: 'BESS-LFP-5.12KWH',
        icon: '🔋',
        badge: '5.12 kWh / 100Ah',
        pvWp: 0,
        poeWatts: 0,
        bessKwh: 5.12,
        voltage: '48V - 51.2V DC',
        ports: ['Terminal (+) (-)', 'CAN/RS485 BMS'],
        color: '#10b981'
      },
      bess_commercial_cabinet: {
        category: 'BESS',
        label: 'Gabinete BESS 30kWh Industrial',
        model: 'BESS-CAB-30KWH-HV',
        icon: '🗄️',
        badge: '30 kWh / 400V DC',
        pvWp: 0,
        poeWatts: 0,
        bessKwh: 30.0,
        voltage: '400V DC Alto Voltaje',
        ports: ['DC Bus HV (+)(-)', 'BMS Ethernet', 'Extinción Incendios'],
        color: '#059669'
      },
      elec_panel: {
        category: 'Eléctrico',
        label: 'Tablero AC / Transferencia ATS',
        model: 'ATS-AC-100A',
        icon: '🔌',
        badge: '120/240V AC',
        pvWp: 0,
        poeWatts: 0,
        bessKwh: 0,
        voltage: '120/240V Bifásico',
        ports: ['Red Pública', 'Generador/Inv', 'Cargas Críticas'],
        color: '#dc2626'
      },

      // 3. CCTV
      cam_dome: {
        category: 'CCTV',
        label: 'Cámara Domo IP',
        model: 'IPC-D240-G2',
        icon: '🎥',
        badge: 'PoE 7W',
        poeWatts: 7,
        pvWp: 0,
        bessKwh: 0,
        voltage: '48V PoE',
        ports: ['RJ45 PoE'],
        color: '#0284c7'
      },
      cam_bullet: {
        category: 'CCTV',
        label: 'Cámara Bullet 4K',
        model: 'IPC-B480-4K',
        icon: '📹',
        badge: 'PoE 9W',
        poeWatts: 9,
        pvWp: 0,
        bessKwh: 0,
        voltage: '48V PoE',
        ports: ['RJ45 PoE'],
        color: '#0284c7'
      },
      cam_ptz: {
        category: 'CCTV',
        label: 'Cámara PTZ 360°',
        model: 'PTZ-36X-PRO',
        icon: '🛰️',
        badge: 'Hi-PoE 25W',
        poeWatts: 25,
        pvWp: 0,
        bessKwh: 0,
        voltage: '56V Hi-PoE',
        ports: ['RJ45 PoE+'],
        color: '#0369a1'
      },
      nvr_server: {
        category: 'CCTV',
        label: 'NVR VMS 32 Canales',
        model: 'NVR-8032-4K',
        icon: '🗄️',
        badge: '120V AC',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: '110-240V AC',
        ports: ['2x LAN GbE', 'HDMI', 'Alarma I/O'],
        color: '#0f766e'
      },

      // 4. CONTROL DE ACCESO
      acs_panel: {
        category: 'Acceso',
        label: 'Controlador de Puertas 4P',
        model: 'AC-404-IP',
        icon: '🎛️',
        badge: '12V DC / LAN',
        poeWatts: 15,
        pvWp: 0,
        bessKwh: 0,
        voltage: '12V DC',
        ports: ['4x Wiegand/OSDP', 'LAN', '4x Relé'],
        color: '#0d9488'
      },
      acs_reader: {
        category: 'Acceso',
        label: 'Lectora RFID/Mifare',
        model: 'RD-1356-M',
        icon: '💳',
        badge: 'Wiegand',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: '12V DC',
        ports: ['Wiegand / RS-485'],
        color: '#14b8a6'
      },
      acs_maglock: {
        category: 'Acceso',
        label: 'Cerradura Maglock 600lb',
        model: 'ML-600-LED',
        icon: '🧲',
        badge: '12V 500mA',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: '12V DC',
        ports: ['Alimentación 12V'],
        color: '#0f766e'
      },
      acs_rex: {
        category: 'Acceso',
        label: 'Pulsador de Salida REX',
        model: 'REX-NO-NC',
        icon: '🔘',
        badge: 'NO/NC',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: 'Pasivo',
        ports: ['Contacto Seco'],
        color: '#115e59'
      },

      // 5. REDES & IT
      net_switch_poe: {
        category: 'Redes',
        label: 'Switch 24P PoE+ L2+',
        model: 'SW-24-POE-370W',
        icon: '🔀',
        badge: 'PoE Budget 370W',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: '120/220V AC',
        ports: ['24x PoE+', '4x SFP+ 10G'],
        color: '#4f46e5'
      },
      net_router: {
        category: 'Redes',
        label: 'Router Gateway Firewall',
        model: 'FW-CORE-10G',
        icon: '🛡️',
        badge: 'Dual-WAN',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: '120/220V AC',
        ports: ['WAN1', 'WAN2', 'LAN SFP+'],
        color: '#4338ca'
      },
      net_ap: {
        category: 'Redes',
        label: 'Access Point Wi-Fi 6',
        model: 'AP-AX3000-PRO',
        icon: '📶',
        badge: 'PoE 13W',
        poeWatts: 13,
        pvWp: 0,
        bessKwh: 0,
        voltage: '48V PoE',
        ports: ['1x GbE PoE'],
        color: '#6366f1'
      },
      net_rack: {
        category: 'Redes',
        label: 'Gabinete Rack 24U',
        model: 'RK-24U-DEPTH800',
        icon: '🚪',
        badge: 'Estructura',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: 'N/A',
        ports: ['PDU AC', 'Tierra Física'],
        color: '#334155'
      },

      // 6. IOT & AUTOMATIZACIÓN
      iot_gateway: {
        category: 'IoT',
        label: 'Gateway LoRaWAN / MQTT',
        model: 'GW-LORA-915-IP67',
        icon: '🛰️',
        badge: 'LoRa/PoE',
        poeWatts: 10,
        pvWp: 0,
        bessKwh: 0,
        voltage: 'PoE 48V',
        ports: ['RJ45 PoE', 'Antena 915MHz'],
        color: '#7c3aed'
      },
      iot_sensor: {
        category: 'IoT',
        label: 'Sensor Temp/Hum/Presencia',
        model: 'SNS-TH-LORA',
        icon: '🌡️',
        badge: 'Inalámbrico',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: '3.6V Batería Li',
        ports: ['RF LoRaWAN'],
        color: '#9333ea'
      },
      iot_plc: {
        category: 'IoT',
        label: 'PLC / RTU Industrial IoT',
        model: 'PLC-IOT-16IO',
        icon: '⚙️',
        badge: '24V DC / Modbus',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: '24V DC',
        ports: ['Ethernet', 'RS-485 Modbus', '8x DI / 8x DO'],
        color: '#6d28d9'
      },
      iot_smart_meter: {
        category: 'IoT',
        label: 'Medidor Bidireccional IoT',
        model: 'MTR-IOT-3PH',
        icon: '📊',
        badge: 'RS-485 / Modbus',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: 'AC 100-277V',
        ports: ['3x TC Toroides', 'RS-485'],
        color: '#a855f7'
      },

      // 7. CANALIZACIONES Y CAJAS (TIA-569 / NEC)
      box_junction_4x4: {
        category: 'Canalización',
        label: 'Caja de Paso Cuadrada 4"x4"',
        model: 'CJ-4X4-EMT',
        icon: '📦',
        badge: 'Acero Galvanizado',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: 'N/A',
        ports: ['KO 1/2" - 3/4"'],
        color: '#0891b2'
      },
      box_pull_nema: {
        category: 'Canalización',
        label: 'Gabinete Registro NEMA 12"x12"',
        model: 'REG-12X12X6-NEMA1',
        icon: '🗃️',
        badge: 'Caja Halado TIA-569',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: 'N/A',
        ports: ['Entradas Múltiples'],
        color: '#0e7490'
      },
      condulet_tee: {
        category: 'Canalización',
        label: 'Condulet Tipo T / LB 3/4"',
        model: 'COND-T-3/4-AL',
        icon: '🪜',
        badge: 'Aluminio Con Tapa',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: 'N/A',
        ports: ['Rosca NPT 3/4"'],
        color: '#155e75'
      },
      box_chalupa: {
        category: 'Canalización',
        label: 'Caja Rectangular 2"x4" (Chalupa)',
        model: 'CJ-2X4-EMT',
        icon: '🔲',
        badge: 'Para Faceplate / REX',
        poeWatts: 0,
        pvWp: 0,
        bessKwh: 0,
        voltage: 'N/A',
        ports: ['KO 1/2"'],
        color: '#164e63'
      }
    };

    // CONFIGURACIÓN DE CABLES Y CANALIZACIONES
    const CABLE_CONFIGS = {
      pv_dc: { name: 'Cable Solar DC 1500V H1Z2Z2-K (6mm²)', color: '#f59e0b', dash: 'none', width: 3.4, marker: 'url(#arrow-pv)', type: 'cable' },
      pv_ground: { name: 'Cable Puesta a Tierra Solar (16mm²)', color: '#84cc16', dash: '4,3', width: 2.8, marker: 'url(#arrow-pv-ground)', type: 'cable' },
      ac_power: { name: 'Alimentación AC (F+N+T)', color: '#ef4444', dash: 'none', width: 3.0, marker: 'url(#arrow-ac)', type: 'cable' },
      poe: { name: 'Cat6 UTP / PoE+', color: '#38bdf8', dash: 'none', width: 2.5, marker: 'url(#arrow-poe)', type: 'cable' },
      fiber: { name: 'Fibra Óptica OM3/OS2', color: '#ec4899', dash: 'none', width: 2.5, marker: 'url(#arrow-fiber)', type: 'cable' },
      wiegand: { name: 'Wiegand / RS-485 Blindado', color: '#10b981', dash: '3,3', width: 2.2, marker: 'url(#arrow-wiegand)', type: 'cable' },
      wireless: { name: 'Enlace RF / Wi-Fi / LoRa', color: '#a855f7', dash: '5,5', width: 2.0, marker: 'none', type: 'cable' },
      
      // Canalizaciones normadas TIA-569 / NEC Art. 358 y 392
      conduit_emt_34: { name: 'Tubería Conduit EMT 3/4"', color: '#22d3ee', dash: 'none', width: 6.0, marker: 'none', type: 'pathway', innerDiaMm: 20.9 },
      conduit_emt_1: { name: 'Tubería Conduit EMT 1"', color: '#06b6d4', dash: 'none', width: 8.0, marker: 'none', type: 'pathway', innerDiaMm: 26.6 },
      conduit_pvc_1: { name: 'Tubería PVC Cédula 40 1"', color: '#0891b2', dash: 'none', width: 8.5, marker: 'none', type: 'pathway', innerDiaMm: 26.0 },
      tray_mesh_150: { name: 'Bandeja Tipo Malla 150x50mm', color: '#0284c7', dash: 'none', width: 12.0, marker: 'none', type: 'pathway', trayPattern: true },
      tray_ladder_300: { name: 'Escalerilla Portacables 300x100mm', color: '#0369a1', dash: 'none', width: 16.0, marker: 'none', type: 'pathway', trayPattern: true }
    };

    // --- UTILIDADES Y TOAST NOTIFICATIONS ---
    function showToast(message, icon = 'ℹ️') {
      const toast = document.getElementById('toastNotification');
      const iconSpan = document.getElementById('toastIcon');
      const msgSpan = document.getElementById('toastMessage');
      if (!toast || !iconSpan || !msgSpan) return;

      iconSpan.innerText = icon;
      msgSpan.innerText = message;
      toast.classList.remove('opacity-0', 'translate-y-20');
      toast.classList.add('opacity-100', 'translate-y-0');

      clearTimeout(APP_STATE._toastTimer);
      APP_STATE._toastTimer = setTimeout(() => {
        toast.classList.remove('opacity-100', 'translate-y-0');
        toast.classList.add('opacity-0', 'translate-y-20');
      }, 2500);
    }

    function toggleDropdown(id) {
      const el = document.getElementById(id);
      if (!el) return;
      document.querySelectorAll('#templatesDropdown, #exportDropdown').forEach(d => {
        if (d.id !== id) d.classList.add('hidden');
      });
      el.classList.toggle('hidden');
    }

    window.addEventListener('click', (e) => {
      if (!e.target.closest('#templatesDropdown') && !e.target.closest('button[onclick*="templatesDropdown"]')) {
        document.getElementById('templatesDropdown')?.classList.add('hidden');
      }
      if (!e.target.closest('#exportDropdown') && !e.target.closest('button[onclick*="exportDropdown"]')) {
        document.getElementById('exportDropdown')?.classList.add('hidden');
      }
    });

    // --- GESTIÓN DE PLANO DE FONDO Y CALIBRACIÓN DE ESCALA ---
    function handleFloorPlanUpload(event) {
      const file = event.target.files[0];
      if (!file) return;

      const reader = new FileReader();
      reader.onload = (e) => {
        APP_STATE.floorPlanDataUrl = e.target.result;
        const img = document.getElementById('floorPlanImg');
        img.src = APP_STATE.floorPlanDataUrl;
        
        img.onload = () => {
          document.getElementById('floorPlanWrapper').classList.remove('hidden');
          document.getElementById('planControlBar').classList.remove('hidden');
          showToast('Plano arquitectónico cargado. Calibra la escala si lo requieres.', '📐');
        };
      };
      reader.readAsDataURL(file);
      event.target.value = '';
    }

    function changePlanOpacity(val) {
      APP_STATE.floorPlanOpacity = val / 100;
      const img = document.getElementById('floorPlanImg');
      if (img) img.style.opacity = APP_STATE.floorPlanOpacity;
    }

    function togglePlanVisibility() {
      APP_STATE.floorPlanVisible = !APP_STATE.floorPlanVisible;
      const wrap = document.getElementById('floorPlanWrapper');
      if (APP_STATE.floorPlanVisible) {
        wrap.classList.remove('hidden');
        showToast('Plano visible');
      } else {
        wrap.classList.add('hidden');
        showToast('Plano oculto');
      }
    }

    function removeFloorPlan() {
      APP_STATE.floorPlanDataUrl = null;
      document.getElementById('floorPlanWrapper').classList.add('hidden');
      document.getElementById('planControlBar').classList.add('hidden');
      showToast('Plano eliminado');
    }

    function startScaleCalibration() {
      setInteractionMode('calibrate');
      APP_STATE.calibrationPoints = [];
      const calLine = document.getElementById('calibrationLine');
      if (calLine) calLine.classList.add('hidden');
      showToast('Haz clic en el primer punto de una cota o muro conocido.', '📏');
    }

    function handleCalibrationClick(canvasX, canvasY) {
      if (APP_STATE.calibrationPoints.length === 0) {
        APP_STATE.calibrationPoints.push({ x: canvasX, y: canvasY });
        const calLine = document.getElementById('calibrationLine');
        if (calLine) {
          calLine.setAttribute('x1', canvasX);
          calLine.setAttribute('y1', canvasY);
          calLine.setAttribute('x2', canvasX);
          calLine.setAttribute('y2', canvasY);
          calLine.classList.remove('hidden');
        }
        showToast('Punto 1 fijado. Haz clic en el segundo extremo.', '📏');
      } else {
        const p1 = APP_STATE.calibrationPoints[0];
        const p2 = { x: canvasX, y: canvasY };
        const distPx = Math.hypot(p2.x - p1.x, p2.y - p1.y);

        if (distPx < 10) {
          showToast('Puntos demasiado cercanos. Intenta nuevamente.');
          APP_STATE.calibrationPoints = [];
          document.getElementById('calibrationLine')?.classList.add('hidden');
          return;
        }

        APP_STATE.calibrationMeasuredPx = distPx;
        document.getElementById('calibratedPixelsSpan').innerText = Math.round(distPx);
        document.getElementById('calibrationModal').classList.remove('hidden');
      }
    }

    function applyScaleCalibration() {
      const realMeters = parseFloat(document.getElementById('realMetersInput').value);
      if (realMeters > 0 && APP_STATE.calibrationMeasuredPx > 0) {
        APP_STATE.scaleMetersPerPixel = realMeters / APP_STATE.calibrationMeasuredPx;
        document.getElementById('scaleLabelText').innerText = `1m = ${Math.round(1 / APP_STATE.scaleMetersPerPixel)}px`;
        showToast(`Escala calibrada: 1m = ${Math.round(1 / APP_STATE.scaleMetersPerPixel)}px`, '✅');
      }
      cancelScaleCalibration();
      updateMetrics();
      renderPathways();
      renderConnections();
    }

    function cancelScaleCalibration() {
      document.getElementById('calibrationModal').classList.add('hidden');
      document.getElementById('calibrationLine')?.classList.add('hidden');
      APP_STATE.calibrationPoints = [];
      setInteractionMode('select');
    }

    // --- GESTIÓN DE MODOS Y TRANSFORMACIÓN DEL LIENZO ---
    function setInteractionMode(mode) {
      APP_STATE.interactionMode = mode;
      const btnSelect = document.getElementById('toolSelect');
      const btnConnect = document.getElementById('toolConnect');
      const btnPathway = document.getElementById('toolPathway');
      const statusDot = document.getElementById('modeStatusDot');
      const statusText = document.getElementById('modeStatusText');

      [btnSelect, btnConnect, btnPathway].forEach(b => {
        if (b) b.className = 'p-1.5 px-3 rounded-lg text-xs font-medium flex items-center gap-1.5 text-slate-300 hover:bg-slate-800 transition';
      });

      APP_STATE.connectingSourceNodeId = null;
      APP_STATE.pathwaySourceNodeId = null;
      document.getElementById('tempCableLine')?.classList.add('hidden');
      document.getElementById('calibrationLine')?.classList.add('hidden');

      if (mode === 'select') {
        if (btnSelect) btnSelect.className = 'p-1.5 px-3 rounded-lg text-xs font-medium flex items-center gap-1.5 bg-indigo-600 text-white transition';
        if (statusDot) statusDot.className = 'w-2.5 h-2.5 rounded-full bg-indigo-500';
        if (statusText) statusText.innerText = 'Modo: Mover y Seleccionar';
      } else if (mode === 'connect') {
        if (btnConnect) btnConnect.className = 'p-1.5 px-3 rounded-lg text-xs font-medium flex items-center gap-1.5 bg-sky-600 text-white transition';
        if (statusDot) statusDot.className = 'w-2.5 h-2.5 rounded-full bg-sky-400 animate-pulse';
        if (statusText) statusText.innerText = 'Modo: Cablear (Haz clic en equipo origen y luego destino)';
      } else if (mode === 'pathway') {
        if (btnPathway) btnPathway.className = 'p-1.5 px-3 rounded-lg text-xs font-medium flex items-center gap-1.5 bg-teal-600 text-white transition';
        if (statusDot) statusDot.className = 'w-2.5 h-2.5 rounded-full bg-teal-400 animate-pulse';
        if (statusText) statusText.innerText = 'Modo: Trazar Canalización (Clic entre cajas o equipos)';
      } else if (mode === 'calibrate') {
        if (statusDot) statusDot.className = 'w-2.5 h-2.5 rounded-full bg-amber-400 animate-pulse';
        if (statusText) statusText.innerText = 'Modo: Calibrar Escala (Clic en 2 extremos conocidos)';
      }

      renderNodes();
    }

    function updateCanvasTransform() {
      const vp = document.getElementById('canvasViewport');
      if (vp) {
        vp.style.transform = `translate(${APP_STATE.panX}px, ${APP_STATE.panY}px) scale(${APP_STATE.zoom})`;
      }
      const zoomText = document.getElementById('zoomLevelText');
      if (zoomText) {
        zoomText.innerText = `${Math.round(APP_STATE.zoom * 100)}%`;
      }
    }

    function zoomCanvas(delta) {
      const newZoom = Math.min(2.5, Math.max(0.3, APP_STATE.zoom + delta));
      APP_STATE.zoom = Math.round(newZoom * 10) / 10;
      updateCanvasTransform();
    }

    function resetZoom() {
      APP_STATE.zoom = 1;
      APP_STATE.panX = 40;
      APP_STATE.panY = 40;
      updateCanvasTransform();
    }

    function toggleGrid() {
      APP_STATE.snapToGrid = !APP_STATE.snapToGrid;
      const btn = document.getElementById('gridToggleBtn');
      if (btn) {
        btn.className = APP_STATE.snapToGrid 
          ? 'p-1.5 hover:bg-slate-800 rounded text-indigo-400 transition text-xs font-mono px-2'
          : 'p-1.5 hover:bg-slate-800 rounded text-slate-500 transition text-xs font-mono px-2';
      }
      showToast(APP_STATE.snapToGrid ? 'Snap a rejilla activado' : 'Snap a rejilla desactivado');
    }

    // --- RENDERIZADO DE CANALIZACIONES (TUBERÍAS / ESCALERILLAS) ---
    function renderPathways() {
      const layer = document.getElementById('pathwaysLayer');
      if (!layer) return;
      layer.innerHTML = '';

      APP_STATE.pathways.forEach(p => {
        const sourceNode = APP_STATE.nodes.find(n => n.id === p.sourceId);
        const targetNode = APP_STATE.nodes.find(n => n.id === p.targetId);

        if (!sourceNode || !targetNode) return;

        const x1 = sourceNode.x + 95;
        const y1 = sourceNode.y + 40;
        const x2 = targetNode.x + 95;
        const y2 = targetNode.y + 40;

        const cfg = CABLE_CONFIGS[p.type] || CABLE_CONFIGS.conduit_emt_34;
        const isSelected = APP_STATE.selectedPathwayId === p.id;

        let pathData = '';
        if (p.routing === 'orthogonal') {
          const midX = (x1 + x2) / 2;
          pathData = `M ${x1} ${y1} L ${midX} ${y1} L ${midX} ${y2} L ${x2} ${y2}`;
        } else {
          pathData = `M ${x1} ${y1} L ${x2} ${y2}`;
        }

        const g = document.createElementNS('http://www.w3.org/2000/svg', 'g');
        g.setAttribute('class', 'pathway-group pointer-events-auto cursor-pointer');

        const casing = document.createElementNS('http://www.w3.org/2000/svg', 'path');
        casing.setAttribute('d', pathData);
        casing.setAttribute('fill', 'none');
        casing.setAttribute('stroke', isSelected ? '#ffffff' : (cfg.color || '#0891b2'));
        casing.setAttribute('stroke-width', (cfg.width + 4).toString());
        casing.setAttribute('stroke-opacity', isSelected ? '0.6' : '0.25');
        casing.setAttribute('stroke-linecap', 'round');

        const path = document.createElementNS('http://www.w3.org/2000/svg', 'path');
        path.setAttribute('d', pathData);
        path.setAttribute('fill', 'none');
        path.setAttribute('stroke', isSelected ? '#38bdf8' : (cfg.trayPattern ? 'url(#trayPattern)' : cfg.color));
        path.setAttribute('stroke-width', cfg.width.toString());
        path.setAttribute('stroke-linecap', 'square');
        path.setAttribute('class', 'pathway-line');

        const hit = document.createElementNS('http://www.w3.org/2000/svg', 'path');
        hit.setAttribute('d', pathData);
        hit.setAttribute('fill', 'none');
        hit.setAttribute('stroke', 'transparent');
        hit.setAttribute('stroke-width', '24');
        hit.addEventListener('click', (e) => {
          e.stopPropagation();
          selectPathway(p.id);
        });

        const midX = (x1 + x2) / 2;
        const midY = (y1 + y2) / 2;

        const text = document.createElementNS('http://www.w3.org/2000/svg', 'text');
        text.setAttribute('x', midX);
        text.setAttribute('y', midY - 6);
        text.setAttribute('fill', isSelected ? '#ffffff' : '#22d3ee');
        text.setAttribute('font-size', '9');
        text.setAttribute('font-weight', 'bold');
        text.setAttribute('font-family', 'JetBrains Mono');
        text.setAttribute('text-anchor', 'middle');
        text.setAttribute('class', 'select-none pointer-events-none');
        
        const lengthMeters = calculatePathwayLength(p, sourceNode, targetNode);
        text.textContent = `${p.label || cfg.name.split(' ')[0]} (${lengthMeters.toFixed(1)}m)`;

        g.appendChild(casing);
        g.appendChild(path);
        g.appendChild(hit);
        g.appendChild(text);
        layer.appendChild(g);
      });
    }

    function calculatePathwayLength(pathway, src, tgt) {
      if (!src || !tgt) return 0;
      const x1 = src.x + 95;
      const y1 = src.y + 40;
      const x2 = tgt.x + 95;
      const y2 = tgt.y + 40;

      let pixelDist = 0;
      if (pathway.routing === 'orthogonal') {
        const midX = (x1 + x2) / 2;
        pixelDist = Math.abs(midX - x1) + Math.abs(y2 - y1) + Math.abs(x2 - midX);
      } else {
        pixelDist = Math.hypot(x2 - x1, y2 - y1);
      }

      return pixelDist * APP_STATE.scaleMetersPerPixel;
    }

    // --- RENDERIZADO DE CABLES Y CONEXIONES ELÉCTRICAS/DATOS ---
    function renderConnections() {
      const layer = document.getElementById('connectionsLayer');
      if (!layer) return;
      layer.innerHTML = '';

      APP_STATE.connections.forEach(conn => {
        const srcNode = APP_STATE.nodes.find(n => n.id === conn.sourceId);
        const tgtNode = APP_STATE.nodes.find(n => n.id === conn.targetId);
        if (!srcNode || !tgtNode) return;

        const x1 = srcNode.x + 95;
        const y1 = srcNode.y + 40;
        const x2 = tgtNode.x + 95;
        const y2 = tgtNode.y + 40;

        const cfg = CABLE_CONFIGS[conn.type] || CABLE_CONFIGS.poe;
        const isSelected = APP_STATE.selectedConnId === conn.id;

        const dx = x2 - x1;
        const dy = y2 - y1;
        const cx1 = x1 + dx * 0.25;
        const cy1 = y1;
        const cx2 = x1 + dx * 0.75;
        const cy2 = y2;
        const d = `M ${x1} ${y1} C ${cx1} ${cy1}, ${cx2} ${cy2}, ${x2} ${y2}`;

        const g = document.createElementNS('http://www.w3.org/2000/svg', 'g');
        g.setAttribute('class', 'pointer-events-auto cursor-pointer');

        const bg = document.createElementNS('http://www.w3.org/2000/svg', 'path');
        bg.setAttribute('d', d);
        bg.setAttribute('fill', 'none');
        bg.setAttribute('stroke', isSelected ? '#ffffff' : cfg.color);
        bg.setAttribute('stroke-width', (cfg.width + (isSelected ? 3 : 1)).toString());
        bg.setAttribute('stroke-opacity', isSelected ? '0.8' : '0.3');

        const line = document.createElementNS('http://www.w3.org/2000/svg', 'path');
        line.setAttribute('d', d);
        line.setAttribute('fill', 'none');
        line.setAttribute('stroke', cfg.color);
        line.setAttribute('stroke-width', cfg.width.toString());
        if (cfg.dash && cfg.dash !== 'none') line.setAttribute('stroke-dasharray', cfg.dash);
        if (cfg.marker && cfg.marker !== 'none') line.setAttribute('marker-end', cfg.marker);
        line.setAttribute('class', 'connector-line');

        const hit = document.createElementNS('http://www.w3.org/2000/svg', 'path');
        hit.setAttribute('d', d);
        hit.setAttribute('fill', 'none');
        hit.setAttribute('stroke', 'transparent');
        hit.setAttribute('stroke-width', '18');
        hit.addEventListener('click', (e) => {
          e.stopPropagation();
          selectConnection(conn.id);
        });

        const midX = (x1 + x2) / 2;
        const midY = (y1 + y2) / 2;

        const text = document.createElementNS('http://www.w3.org/2000/svg', 'text');
        text.setAttribute('x', midX);
        text.setAttribute('y', midY - 6);
        text.setAttribute('fill', isSelected ? '#ffffff' : cfg.color);
        text.setAttribute('font-size', '9');
        text.setAttribute('font-family', 'JetBrains Mono');
        text.setAttribute('text-anchor', 'middle');
        text.setAttribute('class', 'select-none pointer-events-none font-semibold');
        
        const distM = Math.hypot(x2 - x1, y2 - y1) * APP_STATE.scaleMetersPerPixel;
        conn.lengthMeters = Math.max(1, Math.round(distM * 10) / 10);
        text.textContent = `${conn.label || cfg.name.split(' ')[0]} (${conn.lengthMeters}m)`;

        g.appendChild(bg);
        g.appendChild(line);
        g.appendChild(hit);
        g.appendChild(text);
        layer.appendChild(g);
      });
    }

    // --- RENDERIZADO DE NODOS DE EQUIPOS ---
    function renderNodes() {
      const container = document.getElementById('nodesLayer');
      if (!container) return;
      container.innerHTML = '';

      APP_STATE.nodes.forEach(node => {
        const isSelected = APP_STATE.selectedNodeId === node.id;
        const isConnecting = APP_STATE.connectingSourceNodeId === node.id || APP_STATE.pathwaySourceNodeId === node.id;

        const el = document.createElement('div');
        el.id = `node-${node.id}`;
        el.className = `node-card absolute w-48 rounded-xl border bg-slate-900/95 backdrop-blur shadow-xl cursor-grab select-none p-2.5 flex flex-col justify-between ${
          isSelected 
            ? 'ring-2 ring-indigo-500 border-indigo-400 shadow-indigo-500/20' 
            : isConnecting
              ? 'ring-2 ring-amber-400 border-amber-300 animate-pulse'
              : 'border-slate-800 hover:border-slate-700'
        }`;
        el.style.left = `${node.x}px`;
        el.style.top = `${node.y}px`;

        el.innerHTML = `
          <div class="flex items-start justify-between gap-1.5">
            <div class="flex items-center gap-1.5 truncate">
              <span class="text-lg shrink-0">${node.icon || '📦'}</span>
              <div class="truncate">
                <div class="font-semibold text-xs text-slate-100 truncate" title="${node.name}">${node.name}</div>
                <div class="text-[9px] font-mono text-slate-400 truncate">${node.model || node.category}</div>
              </div>
            </div>
            <span class="text-[9px] px-1 py-0.5 rounded font-mono font-medium shrink-0" style="background:${node.color}22; color:${node.color}; border: 1px solid ${node.color}44">
              ${node.badge || node.category}
            </span>
          </div>

          <div class="mt-2 pt-1.5 border-t border-slate-800/80 flex items-center justify-between text-[9px] text-slate-400">
            <span class="font-mono text-slate-300 truncate">${node.ipAddress || (node.voltage || 'DC/AC')}</span>
            <div class="flex items-center gap-1">
              ${node.pvWp ? `<span class="text-amber-400 font-bold">${node.pvWp >= 1000 ? (node.pvWp/1000).toFixed(1)+'kWp' : node.pvWp+'Wp'}</span>` : ''}
              ${node.bessKwh ? `<span class="text-emerald-400 font-bold">${node.bessKwh}kWh</span>` : ''}
              ${node.poeWatts ? `<span class="text-sky-400 font-bold">${node.poeWatts}W</span>` : ''}
            </div>
          </div>
        `;

        el.addEventListener('mousedown', (e) => {
          if (e.button !== 0) return;
          e.stopPropagation();

          if (APP_STATE.interactionMode === 'connect' || APP_STATE.interactionMode === 'pathway') {
            handleNodeConnectClick(node.id);
            return;
          }

          selectNode(node.id);
          APP_STATE.isDraggingNode = true;
          APP_STATE.draggedNodeId = node.id;
          
          const rect = canvasContainer.getBoundingClientRect();
          const canvasMouseX = (e.clientX - rect.left - APP_STATE.panX) / APP_STATE.zoom;
          const canvasMouseY = (e.clientY - rect.top - APP_STATE.panY) / APP_STATE.zoom;
          APP_STATE.dragOffsetX = canvasMouseX - node.x;
          APP_STATE.dragOffsetY = canvasMouseY - node.y;
        });

        container.appendChild(el);
      });
    }

    // --- GESTIÓN DE SELECCIÓN E INSPECTOR ---
    function selectNode(id) {
      APP_STATE.selectedNodeId = id;
      APP_STATE.selectedConnId = null;
      APP_STATE.selectedPathwayId = null;

      const node = APP_STATE.nodes.find(n => n.id === id);
      if (!node) return;

      document.getElementById('inspIcon').innerText = node.icon || '📦';
      document.getElementById('inspTitle').innerText = node.name;
      document.getElementById('inspSubtitle').innerText = `${node.category} • ${node.model}`;
      document.getElementById('deleteSelectedBtn').classList.remove('hidden');

      const body = document.getElementById('inspectorBody');
      body.innerHTML = `
        <div class="space-y-3">
          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Nombre / Identificador</label>
            <input type="text" value="${node.name}" oninput="updateNodeProperty('${node.id}', 'name', this.value)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2.5 py-1.5 text-xs text-slate-100 focus:outline-none focus:border-indigo-500">
          </div>

          <div class="grid grid-cols-2 gap-2">
            <div>
              <label class="block text-[11px] font-medium text-slate-400 mb-1">Categoría</label>
              <input type="text" value="${node.category}" readonly class="w-full bg-slate-950 border border-slate-800 rounded-lg px-2 py-1 text-xs text-slate-400">
            </div>
            <div>
              <label class="block text-[11px] font-medium text-slate-400 mb-1">Modelo / Parte</label>
              <input type="text" value="${node.model}" oninput="updateNodeProperty('${node.id}', 'model', this.value)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2 py-1 text-xs text-slate-200">
            </div>
          </div>

          ${node.category === 'Fotovoltaico' ? `
            <div class="p-3 bg-amber-950/20 border border-amber-900/40 rounded-xl space-y-2">
              <div class="text-[11px] font-bold text-amber-400 uppercase flex items-center justify-between">
                <span>Parámetros Solares (STC)</span>
                <span>☀️</span>
              </div>
              <div class="grid grid-cols-2 gap-2">
                <div>
                  <label class="block text-[10px] text-slate-400">Potencia (Wp)</label>
                  <input type="number" step="10" value="${node.pvWp || 0}" onchange="updateNodeProperty('${node.id}', 'pvWp', parseFloat(this.value)||0)" class="w-full bg-slate-900 border border-slate-700 rounded px-2 py-1 text-xs text-amber-300 font-mono">
                </div>
                <div>
                  <label class="block text-[10px] text-slate-400">Voc (V)</label>
                  <input type="text" value="${node.voltage || '50V'}" oninput="updateNodeProperty('${node.id}', 'voltage', this.value)" class="w-full bg-slate-900 border border-slate-700 rounded px-2 py-1 text-xs text-slate-200 font-mono">
                </div>
              </div>
              <div>
                <label class="block text-[10px] text-slate-400">Corriente Isc / Imp</label>
                <input type="text" value="${node.current || '14A Isc'}" oninput="updateNodeProperty('${node.id}', 'current', this.value)" class="w-full bg-slate-900 border border-slate-700 rounded px-2 py-1 text-xs text-slate-200 font-mono">
              </div>
            </div>
          ` : ''}

          ${node.category === 'BESS' ? `
            <div class="p-3 bg-emerald-950/20 border border-emerald-900/40 rounded-xl space-y-2">
              <div class="text-[11px] font-bold text-emerald-400 uppercase flex items-center justify-between">
                <span>Almacenamiento Litio BESS</span>
                <span>🔋</span>
              </div>
              <div>
                <label class="block text-[10px] text-slate-400">Capacidad BESS (kWh)</label>
                <input type="number" step="0.1" value="${node.bessKwh || 0}" onchange="updateNodeProperty('${node.id}', 'bessKwh', parseFloat(this.value)||0)" class="w-full bg-slate-900 border border-slate-700 rounded px-2 py-1 text-xs text-emerald-300 font-mono">
              </div>
            </div>
          ` : ''}

          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Dirección IP / Host</label>
            <input type="text" value="${node.ipAddress || ''}" placeholder="192.168.1.X" oninput="updateNodeProperty('${node.id}', 'ipAddress', this.value)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2.5 py-1.5 text-xs text-slate-100 font-mono">
          </div>

          <div class="grid grid-cols-2 gap-2">
            <div>
              <label class="block text-[11px] font-medium text-slate-400 mb-1">Consumo PoE (W)</label>
              <input type="number" step="0.5" value="${node.poeWatts || 0}" onchange="updateNodeProperty('${node.id}', 'poeWatts', parseFloat(this.value)||0)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2 py-1 text-xs text-sky-300 font-mono">
            </div>
            <div>
              <label class="block text-[11px] font-medium text-slate-400 mb-1">Alimentación</label>
              <input type="text" value="${node.voltage || ''}" oninput="updateNodeProperty('${node.id}', 'voltage', this.value)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2 py-1 text-xs text-slate-200">
            </div>
          </div>

          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Puertos / Borneras</label>
            <div class="text-[10px] text-slate-400 bg-slate-950 p-2 rounded-lg border border-slate-800/80 font-mono">
              ${(node.ports || ['Conexión estándar']).join(' • ')}
            </div>
          </div>
        </div>
      `;

      renderNodes();
      renderConnections();
    }

    function selectConnection(id) {
      APP_STATE.selectedConnId = id;
      APP_STATE.selectedNodeId = null;
      APP_STATE.selectedPathwayId = null;

      const conn = APP_STATE.connections.find(c => c.id === id);
      if (!conn) return;

      const src = APP_STATE.nodes.find(n => n.id === conn.sourceId);
      const tgt = APP_STATE.nodes.find(n => n.id === conn.targetId);

      document.getElementById('inspIcon').innerText = '🔌';
      document.getElementById('inspTitle').innerText = 'Enlace de Cable';
      document.getElementById('inspSubtitle').innerText = `${src?.name || '?'} ➔ ${tgt?.name || '?'}`;
      document.getElementById('deleteSelectedBtn').classList.remove('hidden');

      const body = document.getElementById('inspectorBody');
      body.innerHTML = `
        <div class="space-y-3">
          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Tipo de Cable / Conductor</label>
            <select onchange="updateConnProperty('${conn.id}', 'type', this.value)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2.5 py-1.5 text-xs text-slate-200">
              <option value="pv_dc" ${conn.type === 'pv_dc' ? 'selected' : ''}>Solar DC 1500V H1Z2Z2-K (6mm²)</option>
              <option value="pv_ground" ${conn.type === 'pv_ground' ? 'selected' : ''}>Cable Tierra Solar 16mm²</option>
              <option value="ac_power" ${conn.type === 'ac_power' ? 'selected' : ''}>AC 120/240V Potencia</option>
              <option value="poe" ${conn.type === 'poe' ? 'selected' : ''}>Cat6 / PoE+ (Red IP)</option>
              <option value="fiber" ${conn.type === 'fiber' ? 'selected' : ''}>Fibra Óptica OM3/OS2</option>
              <option value="wiegand" ${conn.type === 'wiegand' ? 'selected' : ''}>Wiegand / RS-485 Blindado</option>
              <option value="wireless" ${conn.type === 'wireless' ? 'selected' : ''}>Inalámbrico / Wi-Fi</option>
            </select>
          </div>

          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Etiqueta de Identificación</label>
            <input type="text" value="${conn.label || ''}" placeholder="Ej: STR-01-DC" oninput="updateConnProperty('${conn.id}', 'label', this.value)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2.5 py-1.5 text-xs text-slate-200 font-mono">
          </div>

          <div class="grid grid-cols-2 gap-2">
            <div>
              <label class="block text-[11px] font-medium text-slate-400 mb-1">Longitud Estimada</label>
              <div class="text-sky-400 font-mono text-sm py-1 font-bold">${conn.lengthMeters || 0} m</div>
            </div>
            <div>
              <label class="block text-[11px] font-medium text-slate-400 mb-1">Con Holgura (+10%)</label>
              <div class="text-emerald-400 font-mono text-sm py-1 font-bold">${Math.round((conn.lengthMeters || 0) * 1.1 * 10) / 10} m</div>
            </div>
          </div>
        </div>
      `;

      renderNodes();
      renderConnections();
    }

    function selectPathway(id) {
      APP_STATE.selectedPathwayId = id;
      APP_STATE.selectedNodeId = null;
      APP_STATE.selectedConnId = null;

      const p = APP_STATE.pathways.find(item => item.id === id);
      if (!p) return;

      const src = APP_STATE.nodes.find(n => n.id === p.sourceId);
      const tgt = APP_STATE.nodes.find(n => n.id === p.targetId);
      const cfg = CABLE_CONFIGS[p.type] || CABLE_CONFIGS.conduit_emt_34;
      const lengthMeters = calculatePathwayLength(p, src, tgt);

      document.getElementById('inspIcon').innerText = '🏗️';
      document.getElementById('inspTitle').innerText = 'Canalización';
      document.getElementById('inspSubtitle').innerText = `${src?.name || '?'} ➔ ${tgt?.name || '?'}`;
      document.getElementById('deleteSelectedBtn').classList.remove('hidden');

      const body = document.getElementById('inspectorBody');
      body.innerHTML = `
        <div class="space-y-3">
          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Tipo de Canalización (TIA-569 / NEC)</label>
            <select onchange="updatePathwayProperty('${p.id}', 'type', this.value)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2.5 py-1.5 text-xs text-slate-200">
              <option value="conduit_emt_34" ${p.type === 'conduit_emt_34' ? 'selected' : ''}>Tubería EMT 3/4" (Metálica)</option>
              <option value="conduit_emt_1" ${p.type === 'conduit_emt_1' ? 'selected' : ''}>Tubería EMT 1" (Troncal)</option>
              <option value="conduit_pvc_1" ${p.type === 'conduit_pvc_1' ? 'selected' : ''}>Tubería PVC Pesado 1"</option>
              <option value="tray_mesh_150" ${p.type === 'tray_mesh_150' ? 'selected' : ''}>Escalerilla Malla 150mm</option>
              <option value="tray_ladder_300" ${p.type === 'tray_ladder_300' ? 'selected' : ''}>Escalerilla Tipo Escalera 300mm</option>
            </select>
          </div>

          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Trazado / Ruteo</label>
            <select onchange="updatePathwayProperty('${p.id}', 'routing', this.value)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2.5 py-1.5 text-xs text-slate-200">
              <option value="orthogonal" ${p.routing === 'orthogonal' ? 'selected' : ''}>Ortogonal (Escuadra 90°)</option>
              <option value="direct" ${p.routing === 'direct' ? 'selected' : ''}>Directo (Línea Recta)</option>
            </select>
          </div>

          <div>
            <label class="block text-[11px] font-medium text-slate-400 mb-1">Etiqueta de Identificación</label>
            <input type="text" value="${p.label || ''}" placeholder="Ej: TUB-SOLAR-01" oninput="updatePathwayProperty('${p.id}', 'label', this.value)" class="w-full bg-slate-900 border border-slate-800 rounded-lg px-2.5 py-1.5 text-xs text-slate-200 font-mono">
          </div>

          <div class="grid grid-cols-2 gap-2">
            <div>
              <label class="block text-[11px] font-medium text-slate-400 mb-1">Longitud Neta</label>
              <div class="text-cyan-400 font-mono text-sm py-1 font-bold">${lengthMeters.toFixed(1)} m</div>
            </div>
            <div>
              <label class="block text-[11px] font-medium text-slate-400 mb-1">Con Merma (+5%)</label>
              <div class="text-emerald-400 font-mono text-sm py-1 font-bold">${(lengthMeters * 1.05).toFixed(1)} m</div>
            </div>
          </div>

          <div class="p-2.5 rounded-lg bg-slate-950 border border-slate-800 text-[11px] text-slate-400 space-y-1">
            <div class="text-slate-300 font-semibold text-[10px] uppercase">Cálculo de Fijación & Coplado</div>
            <div>• Tubos requeridos (3m c/u): <span class="text-slate-100 font-mono">${Math.ceil((lengthMeters * 1.05) / 3)} tubos</span></div>
            <div>• Coples/Uniones: <span class="text-slate-100 font-mono">${Math.max(1, Math.ceil(lengthMeters / 3))} pzas</span></div>
            <div>• Abrazaderas (c/1.5m): <span class="text-slate-100 font-mono">${Math.ceil(lengthMeters / 1.5) + 1} pzas</span></div>
          </div>
        </div>
      `;

      renderNodes();
      renderConnections();
      renderPathways();
    }

    function deselectAll() {
      APP_STATE.selectedNodeId = null;
      APP_STATE.selectedConnId = null;
      APP_STATE.selectedPathwayId = null;
      document.getElementById('deleteSelectedBtn').classList.add('hidden');
      document.getElementById('inspIcon').innerText = '⚙️';
      document.getElementById('inspTitle').innerText = 'Propiedades';
      document.getElementById('inspSubtitle').innerText = 'Selecciona un equipo o cable';
      document.getElementById('inspectorBody').innerHTML = `
        <div class="text-center py-12 text-slate-500">
          <svg class="w-10 h-10 mx-auto mb-2 text-slate-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122"/></svg>
          <p class="font-medium text-slate-400">Sin Selección</p>
          <p class="text-[11px] mt-1 max-w-[200px] mx-auto">Haz clic en cualquier panel solar, inversor, switch o tubería para configurar sus parámetros.</p>
        </div>
      `;
      renderNodes();
      renderConnections();
      renderPathways();
    }

    function updateNodeProperty(id, prop, val) {
      const node = APP_STATE.nodes.find(n => n.id === id);
      if (node) {
        node[prop] = val;
        updateMetrics();
        renderNodes();
      }
    }

    function updateConnProperty(id, prop, val) {
      const conn = APP_STATE.connections.find(c => c.id === id);
      if (conn) {
        conn[prop] = val;
        renderConnections();
      }
    }

    function updatePathwayProperty(id, prop, val) {
      const p = APP_STATE.pathways.find(item => item.id === id);
      if (p) {
        p[prop] = val;
        renderPathways();
        updateMetrics();
      }
    }

    function deleteSelected() {
      if (APP_STATE.selectedNodeId) {
        const id = APP_STATE.selectedNodeId;
        APP_STATE.nodes = APP_STATE.nodes.filter(n => n.id !== id);
        APP_STATE.connections = APP_STATE.connections.filter(c => c.sourceId !== id && c.targetId !== id);
        APP_STATE.pathways = APP_STATE.pathways.filter(p => p.sourceId !== id && p.targetId !== id);
        showToast('Elemento eliminado');
        deselectAll();
      } else if (APP_STATE.selectedConnId) {
        const id = APP_STATE.selectedConnId;
        APP_STATE.connections = APP_STATE.connections.filter(c => c.id !== id);
        showToast('Cable eliminado');
        deselectAll();
      } else if (APP_STATE.selectedPathwayId) {
        const id = APP_STATE.selectedPathwayId;
        APP_STATE.pathways = APP_STATE.pathways.filter(p => p.id !== id);
        showToast('Canalización eliminada');
        deselectAll();
      }
      updateMetrics();
    }

    // --- MANEJO DE CONEXIÓN ENTRE NODOS Y TRAZADO ---
    function handleNodeConnectClick(nodeId) {
      if (APP_STATE.interactionMode === 'connect') {
        if (!APP_STATE.connectingSourceNodeId) {
          APP_STATE.connectingSourceNodeId = nodeId;
          renderNodes();
          showToast('Selecciona el nodo destino para tender el cable', '🔌');
        } else if (APP_STATE.connectingSourceNodeId === nodeId) {
          APP_STATE.connectingSourceNodeId = null;
          document.getElementById('tempCableLine')?.classList.add('hidden');
          renderNodes();
        } else {
          const selectedType = document.getElementById('cableTypeSelect')?.value || 'pv_dc';
          const cableType = CABLE_CONFIGS[selectedType]?.type === 'cable' ? selectedType : 'pv_dc';

          const newConn = {
            id: 'conn_' + Date.now(),
            sourceId: APP_STATE.connectingSourceNodeId,
            targetId: nodeId,
            type: cableType,
            label: CABLE_CONFIGS[cableType]?.name.split(' ')[0] || 'Enlace',
            lengthMeters: 5
          };

          APP_STATE.connections.push(newConn);
          APP_STATE.connectingSourceNodeId = null;
          document.getElementById('tempCableLine')?.classList.add('hidden');
          renderConnections();
          renderNodes();
          updateMetrics();
          showToast('Cable conectado exitosamente', '✅');
        }
      } else if (APP_STATE.interactionMode === 'pathway') {
        if (!APP_STATE.pathwaySourceNodeId) {
          APP_STATE.pathwaySourceNodeId = nodeId;
          renderNodes();
          showToast('Selecciona la caja o equipo destino de la canalización', '🏗️');
        } else if (APP_STATE.pathwaySourceNodeId === nodeId) {
          APP_STATE.pathwaySourceNodeId = null;
          document.getElementById('tempCableLine')?.classList.add('hidden');
          renderNodes();
        } else {
          const selectedType = document.getElementById('cableTypeSelect')?.value || 'conduit_emt_34';
          const pathwayType = CABLE_CONFIGS[selectedType]?.type === 'pathway' ? selectedType : 'conduit_emt_34';

          const newPathway = {
            id: 'pw_' + Date.now(),
            sourceId: APP_STATE.pathwaySourceNodeId,
            targetId: nodeId,
            type: pathwayType,
            routing: 'orthogonal',
            label: CABLE_CONFIGS[pathwayType]?.name.split(' ')[0] || 'Conduit',
            bendsCount: 1
          };

          APP_STATE.pathways.push(newPathway);
          APP_STATE.pathwaySourceNodeId = null;
          document.getElementById('tempCableLine')?.classList.add('hidden');
          renderPathways();
          renderNodes();
          updateMetrics();
          showToast('Canalización trazada', '✅');
        }
      }
    }

    // --- CÁLCULO DE MÉTRICAS Y BALANCES EN VIVO ---
    function updateMetrics() {
      let poeTotal = 0;
      let pvTotalWp = 0;
      let bessTotal = 0;

      APP_STATE.nodes.forEach(node => {
        poeTotal += (parseFloat(node.poeWatts) || 0);
        pvTotalWp += (parseFloat(node.pvWp) || 0);
        bessTotal += (parseFloat(node.bessKwh) || 0);
      });

      let pathwayMetersTotal = 0;
      APP_STATE.pathways.forEach(p => {
        const src = APP_STATE.nodes.find(n => n.id === p.sourceId);
        const tgt = APP_STATE.nodes.find(n => n.id === p.targetId);
        if (src && tgt) {
          pathwayMetersTotal += calculatePathwayLength(p, src, tgt);
        }
      });

      const elPoe = document.getElementById('metricPoeTotal');
      const elPv = document.getElementById('metricPvTotal');
      const elPvDaily = document.getElementById('metricPvDaily');
      const elBess = document.getElementById('metricBessTotal');
      const elPathways = document.getElementById('metricPathwaysTotal');

      const pvKwp = pvTotalWp / 1000;
      const dailySolarKwh = pvKwp * 5.0 * 0.8; // 5 HSP y Performance Ratio 80%

      if (elPoe) elPoe.innerText = `${Math.round(poeTotal)} W`;
      if (elPv) elPv.innerText = `${pvKwp.toFixed(2)} kWp`;
      if (elPvDaily) elPvDaily.innerText = `${dailySolarKwh.toFixed(1)} kWh/d`;
      if (elBess) elBess.innerText = `${bessTotal.toFixed(2)} kWh`;
      if (elPathways) elPathways.innerText = `${pathwayMetersTotal.toFixed(1)} m`;
    }

    // --- ASISTENTE DE CÁLCULO SOLAR FOTOVOLTAICO ---
    function openPvCalculatorModal() {
      document.getElementById('pvCalculatorModal').classList.remove('hidden');
      runPvCalculations();
    }

    function closePvCalculatorModal() {
      document.getElementById('pvCalculatorModal').classList.add('hidden');
    }

    function runPvCalculations() {
      const nMods = parseInt(document.getElementById('calcPvModulesCount')?.value) || 12;
      const wp = parseFloat(document.getElementById('calcPvModuleWp')?.value) || 580;
      const voc = parseFloat(document.getElementById('calcPvVoc')?.value) || 51.2;
      const vmp = parseFloat(document.getElementById('calcPvVmp')?.value) || 43.1;
      const isc = parseFloat(document.getElementById('calcPvIsc')?.value) || 14.2;
      const tMin = parseFloat(document.getElementById('calcPvTmin')?.value) || 0;

      // Corrección de temperatura según NEC 690.7 (coeficiente estándar -0.28%/°C)
      const tempDelta = 25 - tMin;
      const tempCorrectionFactor = 1 + (tempDelta * 0.0028);
      const vocMaxString = (voc * nMods * tempCorrectionFactor);
      const vmpTotal = vmp * nMods;
      const necAmpacity = isc * 1.56; // Regla 125% continuo x 125% radiación NEC 690.8
      const totalPowerKw = (wp * nMods) / 1000;
      const dailyEnergyKwh = totalPowerKw * 5.0 * 0.8; // 5 Horas Sol Pico x 0.8 PR

      document.getElementById('calcResVocMax').innerText = `${vocMaxString.toFixed(1)} V`;
      document.getElementById('calcResVmpTotal').innerText = `${vmpTotal.toFixed(1)} V`;
      document.getElementById('calcResAmpacity').innerText = `${necAmpacity.toFixed(1)} A`;
      document.getElementById('calcResEnergyDaily').innerText = `${dailyEnergyKwh.toFixed(1)} kWh/día`;

      const statusEl = document.getElementById('calcResVocStatus');
      if (vocMaxString > 1000) {
        statusEl.innerHTML = `<span class="text-amber-400 font-bold">⚠️ Excede 1000V DC:</span> Requiere inversor/cables de 1500V DC o reducir módulos a ${Math.floor(1000 / (voc * tempCorrectionFactor))}.`;
      } else {
        statusEl.innerHTML = `<span class="text-emerald-400 font-semibold">✓ Compatible con inversores estándar 1000V DC.</span>`;
      }

      const cableEl = document.getElementById('calcResCableSuggest');
      if (necAmpacity <= 30) {
        cableEl.innerText = `Sugerido: Conductor Solar 4mm² (12 AWG) o 6mm² (10 AWG). Fusible gPV: 20A o 25A.`;
      } else {
        cableEl.innerText = `Sugerido: Conductor Solar 10mm² (8 AWG). Fusible gPV: 32A.`;
      }
    }

    // --- MODAL DE CÓMPUTO DE MATERIALES (BOM) ---
    function openBomModal() {
      const modal = document.getElementById('bomModal');
      if (!modal) return;

      const devTable = document.getElementById('bomDevicesTable');
      const cabTable = document.getElementById('bomCablesTable');
      const pwTable = document.getElementById('bomPathwaysTable');

      // Cuantificación de Equipos Agrupados por Modelo
      const deviceGroups = {};
      APP_STATE.nodes.forEach(n => {
        const key = `${n.category}__${n.model || n.name}`;
        if (!deviceGroups[key]) {
          deviceGroups[key] = {
            count: 0,
            category: n.category,
            name: n.name,
            model: n.model || n.name,
            specs: `${n.voltage || 'N/A'}${n.pvWp ? ` • ${n.pvWp >= 1000 ? (n.pvWp/1000).toFixed(1)+'kWp' : n.pvWp+'Wp'}` : ''}${n.bessKwh ? ` • ${n.bessKwh}kWh` : ''}${n.poeWatts ? ` • ${n.poeWatts}W PoE` : ''}`
          };
        }
        deviceGroups[key].count++;
      });

      if (devTable) {
        devTable.innerHTML = Object.values(deviceGroups).map(d => `
          <tr class="hover:bg-slate-800/40">
            <td class="p-2.5 font-bold font-mono text-emerald-400">${d.count}</td>
            <td class="p-2.5">${d.category}</td>
            <td class="p-2.5 font-medium text-slate-100">${d.model}</td>
            <td class="p-2.5 text-slate-400">${d.specs}</td>
            <td class="p-2.5 text-[10px] text-slate-500 font-mono">Unidad estándar</td>
          </tr>
        `).join('') || `<tr><td colspan="5" class="p-4 text-center text-slate-500">No hay dispositivos en el plano</td></tr>`;
      }

      document.getElementById('bomDevicesCount').innerText = `${APP_STATE.nodes.length} items`;

      // Cuantificación de Canalizaciones
      let totalPathwayMeters = 0;
      const pathwayGroups = {};
      APP_STATE.pathways.forEach(p => {
        const src = APP_STATE.nodes.find(n => n.id === p.sourceId);
        const tgt = APP_STATE.nodes.find(n => n.id === p.targetId);
        const netLength = calculatePathwayLength(p, src, tgt);
        totalPathwayMeters += netLength;

        const cfg = CABLE_CONFIGS[p.type] || CABLE_CONFIGS.conduit_emt_34;
        if (!pathwayGroups[p.type]) {
          pathwayGroups[p.type] = {
            name: cfg.name,
            netLength: 0
          };
        }
        pathwayGroups[p.type].netLength += netLength;
      });

      if (pwTable) {
        pwTable.innerHTML = Object.entries(pathwayGroups).map(([type, data]) => {
          const withWaste = data.netLength * 1.05;
          const pipesCount = Math.ceil(withWaste / 3);
          const clampsCount = Math.ceil(data.netLength / 1.5);
          return `
            <tr class="hover:bg-slate-800/40">
              <td class="p-2.5 font-medium text-slate-100">${data.name}</td>
              <td class="p-2.5 text-slate-400 font-mono text-[10px]">Tramos de 3.0 m (Norma)</td>
              <td class="p-2.5 font-mono text-cyan-300 font-semibold">${data.netLength.toFixed(1)} m</td>
              <td class="p-2.5 font-mono text-emerald-400 font-bold">${withWaste.toFixed(1)} m (${pipesCount} tubos)</td>
              <td class="p-2.5 text-[11px] text-slate-300 font-mono">${pipesCount} coples • ${clampsCount} abrazaderas</td>
            </tr>
          `;
        }).join('') || `<tr><td colspan="5" class="p-4 text-center text-slate-500">No hay canalizaciones trazadas</td></tr>`;
      }

      document.getElementById('bomPathwaysCount').innerText = `${totalPathwayMeters.toFixed(1)} m total`;

      // Cuantificación de Cableado Físico
      if (cabTable) {
        cabTable.innerHTML = APP_STATE.connections.map(c => {
          const src = APP_STATE.nodes.find(n => n.id === c.sourceId);
          const tgt = APP_STATE.nodes.find(n => n.id === c.targetId);
          const cfg = CABLE_CONFIGS[c.type] || CABLE_CONFIGS.pv_dc;
          const netM = c.lengthMeters || 5;
          const withSlopes = Math.round(netM * 1.1 * 10) / 10;
          return `
            <tr class="hover:bg-slate-800/40">
              <td class="p-2.5 font-medium text-slate-200">${cfg.name}</td>
              <td class="p-2.5 text-slate-400">${src?.name || 'Origen'}</td>
              <td class="p-2.5 text-slate-400">${tgt?.name || 'Destino'}</td>
              <td class="p-2.5 font-mono text-sky-300">${netM} m</td>
              <td class="p-2.5 font-mono text-emerald-400 font-bold">${withSlopes} m</td>
              <td class="p-2.5 text-slate-400 font-mono text-[10px]">${c.label || 'Tirada'}</td>
            </tr>
          `;
        }).join('') || `<tr><td colspan="6" class="p-4 text-center text-slate-500">No hay conexiones registradas</td></tr>`;
      }

      document.getElementById('bomCablesCount').innerText = `${APP_STATE.connections.length} enlaces`;

      modal.classList.remove('hidden');
    }

    function closeBomModal() {
      document.getElementById('bomModal').classList.add('hidden');
    }

    function exportBomCSV() {
      let csv = 'CATEGORIA,TIPO / MODELO,DESCRIPCION,CANTIDAD_O_METRADO_NETO,CON_MERMA_O_HOLGURA,NOTAS_NORMATIVAS\n';

      // Dispositivos
      APP_STATE.nodes.forEach(n => {
        csv += `"DISPOSITIVO","${n.model || n.name}","${n.category} - ${n.name}",1,1,"${n.ipAddress ? `IP: ${n.ipAddress}` : ''} ${n.voltage || ''} ${n.pvWp ? `${n.pvWp}Wp` : ''}"\n`;
      });

      // Canalizaciones
      APP_STATE.pathways.forEach(p => {
        const src = APP_STATE.nodes.find(n => n.id === p.sourceId);
        const tgt = APP_STATE.nodes.find(n => n.id === p.targetId);
        const netLength = calculatePathwayLength(p, src, tgt);
        const cfg = CABLE_CONFIGS[p.type] || CABLE_CONFIGS.conduit_emt_34;
        csv += `"CANALIZACION","${cfg.name}","De ${src?.name || '?'} a ${tgt?.name || '?'}",${netLength.toFixed(2)},${(netLength * 1.05).toFixed(2)},"Tubos 3m: ${Math.ceil((netLength * 1.05) / 3)} | Abrazaderas: ${Math.ceil(netLength / 1.5)}"\n`;
      });

      // Cables
      APP_STATE.connections.forEach(c => {
        const src = APP_STATE.nodes.find(n => n.id === c.sourceId);
        const tgt = APP_STATE.nodes.find(n => n.id === c.targetId);
        const cfg = CABLE_CONFIGS[c.type] || CABLE_CONFIGS.pv_dc;
        const netM = c.lengthMeters || 5;
        csv += `"CABLEADO","${cfg.name}","De ${src?.name || '?'} a ${tgt?.name || '?'}",${netM},${(netM * 1.1).toFixed(2)},"Holgura TIA/NEC 10% incluida"\n`;
      });

      const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = `BOM_Fotovoltaico_Seguridad_${new Date().toISOString().slice(0, 10)}.csv`;
      a.click();
      showToast('Cómputo exportado a CSV (Excel)', '📊');
    }

    function addNodeToCanvas(typeKey) {
      const def = COMPONENT_DEFINITIONS[typeKey];
      if (!def) return;

      const offset = (APP_STATE.nodes.length % 8) * 20;
      const x = Math.round((180 + offset - APP_STATE.panX) / (APP_STATE.snapToGrid ? APP_STATE.gridSize : 1)) * (APP_STATE.snapToGrid ? APP_STATE.gridSize : 1);
      const y = Math.round((140 + offset - APP_STATE.panY) / (APP_STATE.snapToGrid ? APP_STATE.gridSize : 1)) * (APP_STATE.snapToGrid ? APP_STATE.gridSize : 1);

      const newNode = {
        id: 'node_' + Date.now(),
        typeKey: typeKey,
        name: `${def.label} ${APP_STATE.nodes.filter(n => n.typeKey === typeKey).length + 1}`,
        category: def.category,
        model: def.model,
        icon: def.icon,
        badge: def.badge,
        color: def.color,
        poeWatts: def.poeWatts || 0,
        pvWp: def.pvWp || 0,
        bessKwh: def.bessKwh || 0,
        voltage: def.voltage || '12V DC',
        current: def.current || '',
        ports: [...(def.ports || [])],
        ipAddress: def.category === 'CCTV' || def.category === 'Redes' ? `192.168.1.${10 + APP_STATE.nodes.length}` : '',
        x: Math.max(20, x),
        y: Math.max(20, y)
      };

      APP_STATE.nodes.push(newNode);
      selectNode(newNode.id);
      updateMetrics();
      showToast(`Añadido: ${newNode.name}`, '➕');
    }

    function filterComponents() {
      const query = document.getElementById('searchComponent').value.toLowerCase();
      const blocks = document.querySelectorAll('#componentLibraryList .category-block');

      blocks.forEach(block => {
        let hasMatch = false;
        const buttons = block.querySelectorAll('.comp-btn');
        buttons.forEach(btn => {
          const text = btn.innerText.toLowerCase();
          if (text.includes(query)) {
            btn.style.display = 'flex';
            hasMatch = true;
          } else {
            btn.style.display = 'none';
          }
        });
        block.style.display = hasMatch ? 'block' : 'none';
      });
    }

    function clearCanvas() {
      if (APP_STATE.nodes.length === 0 && APP_STATE.pathways.length === 0) return;
      APP_STATE.nodes = [];
      APP_STATE.connections = [];
      APP_STATE.pathways = [];
      deselectAll();
      updateMetrics();
      showToast('Lienzo vaciado', '🗑️');
    }

    // --- GESTIÓN DE EVENTOS DE RATÓN Y TECLADO ---
    const canvasContainer = document.getElementById('canvasContainer');

    canvasContainer.addEventListener('mousedown', (e) => {
      if (e.target === canvasContainer || e.target.id === 'connectionsSvg' || e.target.id === 'nodesLayer' || e.target.id === 'canvasViewport') {
        if (APP_STATE.interactionMode === 'calibrate') {
          const rect = canvasContainer.getBoundingClientRect();
          const canvasX = (e.clientX - rect.left - APP_STATE.panX) / APP_STATE.zoom;
          const canvasY = (e.clientY - rect.top - APP_STATE.panY) / APP_STATE.zoom;
          handleCalibrationClick(canvasX, canvasY);
          return;
        }

        deselectAll();

        APP_STATE.isPanning = true;
        APP_STATE.panStartX = e.clientX - APP_STATE.panX;
        APP_STATE.panStartY = e.clientY - APP_STATE.panY;
      }
    });

    window.addEventListener('mousemove', (e) => {
      const rect = canvasContainer.getBoundingClientRect();
      const canvasMouseX = (e.clientX - rect.left - APP_STATE.panX) / APP_STATE.zoom;
      const canvasMouseY = (e.clientY - rect.top - APP_STATE.panY) / APP_STATE.zoom;

      // Paneo del lienzo
      if (APP_STATE.isPanning) {
        APP_STATE.panX = e.clientX - APP_STATE.panStartX;
        APP_STATE.panY = e.clientY - APP_STATE.panStartY;
        updateCanvasTransform();
        return;
      }

      // Arrastre de nodo
      if (APP_STATE.isDraggingNode && APP_STATE.draggedNodeId) {
        const node = APP_STATE.nodes.find(n => n.id === APP_STATE.draggedNodeId);
        if (node) {
          let targetX = canvasMouseX - APP_STATE.dragOffsetX;
          let targetY = canvasMouseY - APP_STATE.dragOffsetY;

          if (APP_STATE.snapToGrid) {
            targetX = Math.round(targetX / APP_STATE.gridSize) * APP_STATE.gridSize;
            targetY = Math.round(targetY / APP_STATE.gridSize) * APP_STATE.gridSize;
          }

          node.x = Math.max(0, targetX);
          node.y = Math.max(0, targetY);

          const el = document.getElementById(`node-${node.id}`);
          if (el) {
            el.style.left = `${node.x}px`;
            el.style.top = `${node.y}px`;
          }

          renderConnections();
          renderPathways();
        }
        return;
      }

      // Línea temporal al cablear o trazar canalización
      const activeSourceId = APP_STATE.connectingSourceNodeId || APP_STATE.pathwaySourceNodeId;
      if (activeSourceId) {
        const src = APP_STATE.nodes.find(n => n.id === activeSourceId);
        const tempLine = document.getElementById('tempCableLine');
        if (src && tempLine) {
          tempLine.setAttribute('x1', src.x + 95);
          tempLine.setAttribute('y1', src.y + 40);
          tempLine.setAttribute('x2', canvasMouseX);
          tempLine.setAttribute('y2', canvasMouseY);
          tempLine.classList.remove('hidden');
        }
      }

      // Línea de calibración
      if (APP_STATE.interactionMode === 'calibrate' && APP_STATE.calibrationPoints.length === 1) {
        const p1 = APP_STATE.calibrationPoints[0];
        const calLine = document.getElementById('calibrationLine');
        if (calLine) {
          calLine.setAttribute('x1', p1.x);
          calLine.setAttribute('y1', p1.y);
          calLine.setAttribute('x2', canvasMouseX);
          calLine.setAttribute('y2', canvasMouseY);
        }
      }
    });

    window.addEventListener('mouseup', () => {
      APP_STATE.isPanning = false;
      APP_STATE.isDraggingNode = false;
      APP_STATE.draggedNodeId = null;
    });

    canvasContainer.addEventListener('wheel', (e) => {
      e.preventDefault();
      const zoomFactor = e.deltaY < 0 ? 0.08 : -0.08;
      zoomCanvas(zoomFactor);
    }, { passive: false });

    // Atajos de Teclado
    window.addEventListener('keydown', (e) => {
      if (e.target.tagName === 'INPUT' || e.target.tagName === 'TEXTAREA' || e.target.tagName === 'SELECT') return;

      if (e.key === 'v' || e.key === 'V') setInteractionMode('select');
      if (e.key === 'c' || e.key === 'C') setInteractionMode('connect');
      if (e.key === 'p' || e.key === 'P') setInteractionMode('pathway');
      if (e.key === 'Delete' || e.key === 'Backspace') deleteSelected();
      if (e.key === 'Escape') {
        APP_STATE.connectingSourceNodeId = null;
        APP_STATE.pathwaySourceNodeId = null;
        document.getElementById('tempCableLine')?.classList.add('hidden');
        deselectAll();
      }
    });

    // --- PLANTILLAS PREDISEÑADAS ---
    function loadTemplate(key) {
      APP_STATE.nodes = [];
      APP_STATE.connections = [];
      APP_STATE.pathways = [];
      deselectAll();

      if (key === 'pv_commercial') {
        APP_STATE.nodes = [
          { id: 'str1', typeKey: 'pv_string', name: 'String Solar A (12x 580W)', model: 'STR-12X-580W', category: 'Fotovoltaico', x: 80, y: 80, ipAddress: '', poeWatts: 0, pvWp: 6960, bessKwh: 0, voltage: '614V Voc', icon: '☀️', color: '#f59e0b', badge: '6.96 kWp' },
          { id: 'str2', typeKey: 'pv_string', name: 'String Solar B (12x 580W)', model: 'STR-12X-580W', category: 'Fotovoltaico', x: 80, y: 220, ipAddress: '', poeWatts: 0, pvWp: 6960, bessKwh: 0, voltage: '614V Voc', icon: '☀️️', color: '#f59e0b', badge: '6.96 kWp' },
          { id: 'cbox', typeKey: 'pv_combiner_box', name: 'Combiner Box DC 1000V', model: 'CB-4IN-1OUT-1000V', category: 'Fotovoltaico', x: 380, y: 150, ipAddress: '', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '1000V DC', icon: '🧰', color: '#d97706', badge: 'Fusibles + DPS' },
          { id: 'inv_grid', typeKey: 'pv_inverter_string', name: 'Inversor String 15kW Tri.', model: 'INV-GRID-15K-2MPPT', category: 'Fotovoltaico', x: 640, y: 150, ipAddress: '192.168.1.185', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '480V / 277V AC', icon: '⚡', color: '#f59e0b', badge: '15kW On-Grid' },
          { id: 'mtr1', typeKey: 'iot_smart_meter', name: 'Medidor Smart Zero-Export', model: 'MTR-IOT-3PH', category: 'IoT', x: 880, y: 150, ipAddress: '', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '277/480V AC', icon: '📊', color: '#a855f7', badge: 'RS-485 Modbus' },
          { id: 'gnd', typeKey: 'pv_spd_ground', name: 'Barra Tierra & Bajante PE', model: 'PROT-DPS-1000V-T2', category: 'Fotovoltaico', x: 380, y: 300, ipAddress: '', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '< 10 Ohms', icon: '⚡', color: '#84cc16', badge: 'Tierra Solar' }
        ];

        APP_STATE.connections = [
          { id: 'c_pv1', sourceId: 'str1', targetId: 'cbox', type: 'pv_dc', label: 'String A DC', lengthMeters: 18 },
          { id: 'c_pv2', sourceId: 'str2', targetId: 'cbox', type: 'pv_dc', label: 'String B DC', lengthMeters: 22 },
          { id: 'c_pv3', sourceId: 'cbox', targetId: 'inv_grid', type: 'pv_dc', label: 'Troncal DC 1000V', lengthMeters: 8 },
          { id: 'c_ac1', sourceId: 'inv_grid', targetId: 'mtr1', type: 'ac_power', label: 'Salida AC Inversor', lengthMeters: 6 },
          { id: 'c_gnd1', sourceId: 'cbox', targetId: 'gnd', type: 'pv_ground', label: 'Bajante Tierra 16mm²', lengthMeters: 12 }
        ];

        APP_STATE.pathways = [
          { id: 'pw_pv1', sourceId: 'str1', targetId: 'cbox', type: 'conduit_emt_1', routing: 'orthogonal', label: 'EMT 1" Solar', bendsCount: 1 },
          { id: 'pw_pv2', sourceId: 'cbox', targetId: 'inv_grid', type: 'conduit_emt_1', routing: 'orthogonal', label: 'EMT 1" Troncal', bendsCount: 1 }
        ];
      } else if (key === 'bess_pv') {
        APP_STATE.nodes = [
          { id: 'pv1', typeKey: 'pv_string', name: 'Arreglo Solar Techo A', model: 'STR-10X-580W', category: 'Fotovoltaico', x: 100, y: 100, ipAddress: '', poeWatts: 0, pvWp: 5800, bessKwh: 0, voltage: '512V Voc', icon: '☀️️', color: '#f59e0b', badge: '5.8 kWp DC' },
          { id: 'inv1', typeKey: 'pv_inverter', name: 'Inversor Híbrido 6kW', model: 'INV-HYBRID-6K-48V', category: 'Fotovoltaico', x: 380, y: 180, ipAddress: '192.168.1.180', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '48V DC / 230V AC', icon: '🔄', color: '#f59e0b', badge: '6kW Inverter' },
          { id: 'bat1', typeKey: 'bess_battery', name: 'Rack Batería Litio #1', model: 'BESS-LFP-5.12KWH', category: 'BESS', x: 100, y: 280, ipAddress: '', poeWatts: 0, pvWp: 0, bessKwh: 5.12, voltage: '48V DC', icon: '🔋', color: '#10b981', badge: '5.12 kWh' },
          { id: 'panel1', typeKey: 'elec_panel', name: 'Tablero Transferencia ATS', model: 'ATS-AC-100A', category: 'Eléctrico', x: 660, y: 180, ipAddress: '', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '120/240V AC', icon: '🔌', color: '#dc2626', badge: '120/240V' }
        ];

        APP_STATE.connections = [
          { id: 'cpv1', sourceId: 'pv1', targetId: 'inv1', type: 'pv_dc', label: 'DC Solar String', lengthMeters: 22 },
          { id: 'cbat1', sourceId: 'bat1', targetId: 'inv1', type: 'pv_dc', label: 'Alimentación DC 48V', lengthMeters: 5 },
          { id: 'cac1', sourceId: 'inv1', targetId: 'panel1', type: 'ac_power', label: 'Salida AC Respaldo', lengthMeters: 8 }
        ];

        APP_STATE.pathways = [
          { id: 'pw_pv', sourceId: 'pv1', targetId: 'inv1', type: 'conduit_emt_1', routing: 'orthogonal', label: 'EMT 1" Solar', bendsCount: 2 },
          { id: 'pw_ac', sourceId: 'inv1', targetId: 'panel1', type: 'tray_mesh_150', routing: 'orthogonal', label: 'Bandeja Malla AC', bendsCount: 1 }
        ];
      } else if (key === 'cctv_acs') {
        APP_STATE.nodes = [
          { id: 'nvr1', typeKey: 'nvr_server', name: 'NVR Central 32Ch', model: 'NVR-8032-4K', category: 'CCTV', x: 80, y: 180, ipAddress: '192.168.1.100', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '120V AC', icon: '🗄️', color: '#0f766e', badge: '120V AC' },
          { id: 'sw1', typeKey: 'net_switch_poe', name: 'Switch Core PoE+ 24P', model: 'SW-24-POE-370W', category: 'Redes', x: 300, y: 180, ipAddress: '192.168.1.2', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '120V AC', icon: '🔀', color: '#4f46e5', badge: 'PoE 370W' },
          { id: 'box1', typeKey: 'box_junction_4x4', name: 'Caja Paso Pasillo', model: 'CJ-4X4-EMT', category: 'Canalización', x: 540, y: 100, ipAddress: '', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: 'N/A', icon: '📦', color: '#0891b2', badge: 'Conduit' },
          { id: 'cam1', typeKey: 'cam_dome', name: 'Cámara Domo Acceso', model: 'IPC-D240-G2', category: 'CCTV', x: 760, y: 60, ipAddress: '192.168.1.10', poeWatts: 7, pvWp: 0, bessKwh: 0, voltage: '48V PoE', icon: '🎥', color: '#0284c7', badge: 'PoE 7W' },
          { id: 'cam2', typeKey: 'cam_bullet', name: 'Cámara Bullet Perímetro', model: 'IPC-B480-4K', category: 'CCTV', x: 760, y: 160, ipAddress: '192.168.1.11', poeWatts: 9, pvWp: 0, bessKwh: 0, voltage: '48V PoE', icon: '📹', color: '#0284c7', badge: 'PoE 9W' },
          { id: 'acs1', typeKey: 'acs_panel', name: 'Panel Control Acceso 4P', model: 'AC-404-IP', category: 'Acceso', x: 300, y: 350, ipAddress: '192.168.1.50', poeWatts: 15, pvWp: 0, bessKwh: 0, voltage: '12V DC', icon: '🎛️', color: '#0d9488', badge: '12V DC / LAN' },
          { id: 'rdr1', typeKey: 'acs_reader', name: 'Lectora Torniquete Principal', model: 'RD-1356-M', category: 'Acceso', x: 560, y: 350, ipAddress: '', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '12V DC', icon: '💳', color: '#14b8a6', badge: 'Wiegand' }
        ];

        APP_STATE.connections = [
          { id: 'c1', sourceId: 'nvr1', targetId: 'sw1', type: 'poe', label: 'Gigabit LAN', lengthMeters: 4 },
          { id: 'c2', sourceId: 'sw1', targetId: 'cam1', type: 'poe', label: 'Cam 01 PoE', lengthMeters: 28 },
          { id: 'c3', sourceId: 'sw1', targetId: 'cam2', type: 'poe', label: 'Cam 02 PoE', lengthMeters: 32 },
          { id: 'c4', sourceId: 'sw1', targetId: 'acs1', type: 'poe', label: 'LAN Acceso', lengthMeters: 12 },
          { id: 'c5', sourceId: 'acs1', targetId: 'rdr1', type: 'wiegand', label: 'Bus Wiegand', lengthMeters: 15 }
        ];

        APP_STATE.pathways = [
          { id: 'pw1', sourceId: 'sw1', targetId: 'box1', type: 'conduit_emt_1', routing: 'orthogonal', label: 'EMT 1"', bendsCount: 1 },
          { id: 'pw2', sourceId: 'box1', targetId: 'cam1', type: 'conduit_emt_34', routing: 'orthogonal', label: 'EMT 3/4"', bendsCount: 2 },
          { id: 'pw3', sourceId: 'box1', targetId: 'cam2', type: 'conduit_emt_34', routing: 'orthogonal', label: 'EMT 3/4"', bendsCount: 1 }
        ];
      } else if (key === 'iot_net') {
        APP_STATE.nodes = [
          { id: 'gw1', typeKey: 'iot_gateway', name: 'Gateway LoRaWAN Exterior', model: 'GW-LORA-915-IP67', category: 'IoT', x: 500, y: 120, ipAddress: '192.168.1.60', poeWatts: 10, pvWp: 0, bessKwh: 0, voltage: '48V PoE', icon: '🛰️', color: '#7c3aed', badge: 'LoRa/PoE' },
          { id: 'sw_core', typeKey: 'net_switch_poe', name: 'Switch Distribución IT', model: 'SW-24-POE-370W', category: 'Redes', x: 220, y: 180, ipAddress: '192.168.1.1', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '120V AC', icon: '🔀', color: '#4f46e5', badge: 'PoE 370W' },
          { id: 'ap1', typeKey: 'net_ap', name: 'Access Point Oficinas', model: 'AP-AX3000-PRO', category: 'Redes', x: 500, y: 260, ipAddress: '192.168.1.75', poeWatts: 13, pvWp: 0, bessKwh: 0, voltage: '48V PoE', icon: '📶', color: '#6366f1', badge: 'PoE 13W' },
          { id: 'sns1', typeKey: 'iot_sensor', name: 'Sensor Humedad Servidores', model: 'SNS-TH-LORA', category: 'IoT', x: 740, y: 120, ipAddress: '', poeWatts: 0, pvWp: 0, bessKwh: 0, voltage: '3.6V Bat', icon: '🌡️', color: '#9333ea', badge: 'Inalámbrico' }
        ];

        APP_STATE.connections = [
          { id: 'ciot1', sourceId: 'sw_core', targetId: 'gw1', type: 'poe', label: 'Cat6 PoE Gateway', lengthMeters: 18 },
          { id: 'ciot2', sourceId: 'sw_core', targetId: 'ap1', type: 'poe', label: 'Cat6 PoE AP', lengthMeters: 14 },
          { id: 'ciot3', sourceId: 'gw1', targetId: 'sns1', type: 'wireless', label: 'LoRaWAN 915MHz', lengthMeters: 35 }
        ];
      }

      renderNodes();
      renderConnections();
      renderPathways();
      updateMetrics();
      showToast(`Plantilla cargada: ${key}`);
    }

    // --- EXPORTACIÓN E IMPORTACIÓN DE PROYECTO ---
    function exportProjectJSON() {
      const projectData = {
        version: '1.4.0',
        date: new Date().toISOString(),
        nodes: APP_STATE.nodes,
        connections: APP_STATE.connections,
        pathways: APP_STATE.pathways,
        scaleMetersPerPixel: APP_STATE.scaleMetersPerPixel
      };

      const blob = new Blob([JSON.stringify(projectData, null, 2)], { type: 'application/json' });
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = `TechDiagram_Solar_IT_${new Date().toISOString().slice(0, 10)}.json`;
      a.click();
      showToast('Proyecto exportado a JSON', '💾');
    }

    function importProjectJSON(event) {
      const file = event.target.files[0];
      if (!file) return;

      const reader = new FileReader();
      reader.onload = (e) => {
        try {
          const data = JSON.parse(e.target.result);
          if (Array.isArray(data.nodes)) {
            APP_STATE.nodes = data.nodes;
            APP_STATE.connections = data.connections || [];
            APP_STATE.pathways = data.pathways || [];
            if (data.scaleMetersPerPixel) {
              APP_STATE.scaleMetersPerPixel = data.scaleMetersPerPixel;
              document.getElementById('scaleLabelText').innerText = `1m = ${Math.round(1 / APP_STATE.scaleMetersPerPixel)}px`;
            }
            deselectAll();
            renderNodes();
            renderConnections();
            renderPathways();
            updateMetrics();
            showToast('Proyecto cargado exitosamente', '📂');
          }
        } catch (err) {
          showToast('Archivo JSON no válido');
        }
      };
      reader.readAsText(file);
      event.target.value = '';
    }

    function exportDiagramSVG() {
      const svg = document.getElementById('connectionsSvg').cloneNode(true);
      svg.setAttribute('xmlns', 'http://www.w3.org/2000/svg');
      
      const s = new XMLSerializer().serializeToString(svg);
      const blob = new Blob([s], { type: 'image/svg+xml;charset=utf-8' });
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = `Diagrama_Ingenieria_Solar_IT_${new Date().toISOString().slice(0, 10)}.svg`;
      a.click();
      showToast('Diagrama exportado en SVG', '📐');
    }

    // --- INICIALIZACIÓN ---
    window.onload = function() {
      loadTemplate('pv_commercial');
      updateCanvasTransform();
    };
  </script>
</body>
</html>
=======
# TechDiagram-Pro-
Diagramar proyectos especiales
>>>>>>> 1243fde132c0bfede499ffc2ca6a3910d2bb1e14
