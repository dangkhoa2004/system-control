<template>
  <div class="min-h-screen bg-[#f1f5f9] flex justify-center items-center p-4 md:p-8 font-sans text-slate-800">
    
    <div class="relative w-full max-w-[1700px] h-[85vh] bg-white rounded-3xl shadow-[0_20px_60px_-15px_rgba(0,0,0,0.1)] border border-slate-200 overflow-hidden flex flex-col md:flex-row">
        
        <div class="absolute inset-0 z-0 opacity-[0.03]" style="background-image: linear-gradient(#000 1px, transparent 1px), linear-gradient(90deg, #000 1px, transparent 1px); background-size: 40px 40px;"></div>

        <div class="hidden md:block absolute left-[35%] xl:left-[400px] top-12 bottom-12 w-px bg-gradient-to-b from-transparent via-slate-200 to-transparent z-0"></div>

        <div class="relative w-full md:w-[35%] xl:w-[400px] h-full flex items-center justify-center z-10 shrink-0">
            
            <div class="relative flex flex-col items-center justify-center scale-90 md:scale-100">
                <div class="absolute -bottom-8 w-[250px] h-[20px] bg-slate-200 rounded-full blur-xl"></div>
                
                <div class="relative z-30 flex items-end justify-center gap-2 mb-2">
                    <div class="w-[80px] h-[100px] bg-slate-800 rounded-xl border border-slate-600 transform rotate-6 origin-bottom-right shadow-lg flex flex-col p-2">
                        <div class="w-full h-1.5 bg-slate-700 rounded-full mb-1.5"></div>
                        <div class="w-2/3 h-1 bg-slate-600 rounded-full"></div>
                    </div>
                    
                    <div class="w-[160px] h-[115px] bg-slate-900 rounded-xl border border-slate-700 relative z-10 shadow-2xl flex flex-col items-center p-3 justify-between">
                        <div class="text-[9px] font-bold text-slate-400 tracking-widest mt-1">SYSTEM ADMIN</div>
                        <div class="flex gap-3 mb-2">
                            <div class="w-8 h-8 rounded-full border-[2px] border-slate-600"></div>
                            <div class="w-8 h-8 rounded-full border-[2px] border-slate-600"></div>
                        </div>
                        <div class="w-1/2 h-1 bg-slate-700 rounded-full"></div>
                    </div>
                    
                    <div class="w-[80px] h-[100px] bg-slate-800 rounded-xl border border-slate-600 transform -rotate-6 origin-bottom-left shadow-lg flex flex-col p-2 items-end">
                        <div class="w-full h-1.5 bg-slate-700 rounded-full mb-1.5"></div>
                        <div class="w-2/3 h-1 bg-slate-600 rounded-full"></div>
                    </div>
                </div>

                <div class="relative z-40 flex flex-col items-center -mt-8">
                    <div class="w-[84px] h-[84px] rounded-full p-1 bg-white shadow-md border border-slate-200 z-10">
                        <img src="https://picsum.photos/150?random=10" class="w-full h-full rounded-full object-cover grayscale">
                    </div>
                    <div class="bg-slate-800 text-white text-[10px] font-bold px-4 py-1 rounded-full border-2 border-white -mt-3 z-20 shadow-sm uppercase tracking-wider">Admin</div>
                </div>

                <div class="relative w-[320px] h-[120px] bg-white border border-slate-200 rounded-t-xl shadow-[0_10px_20px_rgba(0,0,0,0.03)] mt-[-45px] z-20 flex flex-col justify-end">
                    <div class="w-full h-[12px] bg-slate-50 border-t border-slate-100 flex justify-center gap-10 items-center">
                        <div class="w-10 h-1 bg-slate-200 rounded-full"></div>
                        <div class="w-10 h-1 bg-slate-200 rounded-full"></div>
                    </div>
                    <div class="absolute top-full left-[30px] w-[6px] h-[90px] bg-slate-300 rounded-b-md"></div>
                    <div class="absolute top-full right-[30px] w-[6px] h-[90px] bg-slate-300 rounded-b-md"></div>
                </div>
            </div>

        </div>

        <div class="flex-1 h-full flex items-center justify-center relative z-10">
            <div class="transform scale-[0.55] sm:scale-75 lg:scale-[0.8] xl:scale-90 origin-center transition-transform">
                <Workspace />
            </div>
        </div>

        <div class="absolute bottom-8 left-8 w-[200px] h-[60px] bg-slate-50 border border-slate-200 rounded-2xl shadow-sm flex items-end justify-center pb-2 z-0 hidden lg:flex">
            <div class="w-[180px] h-[15px] bg-slate-200 rounded-md"></div>
            <div class="absolute top-2 left-6 w-[25px] h-[12px] bg-slate-300 rounded-sm"></div>
            <div class="absolute top-2 right-6 w-[25px] h-[12px] bg-slate-300 rounded-sm"></div>
        </div>

        <div class="absolute top-10 right-10 flex gap-3 opacity-60 z-0 hidden sm:flex">
            <div class="w-[35px] h-[35px] bg-slate-50 border border-slate-200 rounded-full shadow-sm flex items-center justify-center">
                <div class="w-[15px] h-[15px] bg-slate-300 rounded-full"></div>
            </div>
            <div class="w-[50px] h-[50px] bg-slate-50 border border-slate-200 rounded-full shadow-sm flex items-center justify-center">
                <div class="w-[25px] h-[25px] bg-slate-300 rounded-full"></div>
            </div>
        </div>

        <div class="absolute top-8 left-8 bg-white/80 backdrop-blur-md px-5 py-3 rounded-2xl shadow-[0_8px_30px_rgb(0,0,0,0.04)] border border-slate-100 z-50">
            <h2 class="font-bold text-slate-800 tracking-widest text-[10px] uppercase">Tech Office Layout</h2>
            <div class="flex items-center gap-2 mt-1.5 text-[11px] font-medium text-slate-500">
                <span class="relative flex h-2 w-2">
                    <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-slate-400 opacity-75"></span>
                    <span class="relative inline-flex rounded-full h-2 w-2 bg-slate-500"></span>
                </span>
                Active Sessions: 5/6
            </div>
        </div>

    </div>
  </div>
</template>

<script setup>
// Giữ nguyên file Workspace.vue (Cụm 2 bàn & 4 bàn) từ trước
import Workspace from './Workspace.vue'
</script>