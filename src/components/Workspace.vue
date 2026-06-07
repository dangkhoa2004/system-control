<template>
    <div class="w-full flex justify-center items-center gap-12 lg:gap-24 font-sans">

        <div
            class="grid grid-cols-1 gap-y-[40px] bg-slate-50/50 p-6 rounded-2xl border-2 border-slate-200/50 shadow-sm">

            <div
                class="group relative w-[340px] h-[280px] flex flex-col items-center justify-end transition-transform duration-400 hover:-translate-y-1.5">
                <div
                    class="absolute -bottom-2.5 w-[280px] h-[20px] bg-[radial-gradient(ellipse_at_center,rgba(0,0,0,0.06)_0%,rgba(0,0,0,0)_70%)] z-10 pointer-events-none">
                </div>

                <div class="absolute w-[160px] h-[120px] bottom-[155px] z-30 flex flex-col items-center justify-start">
                    <div
                        class="w-[160px] h-[94px] rounded border-[3px] border-[#66a3ff] bg-white overflow-hidden relative shadow-[0_4px_10px_rgba(0,0,0,0.05)] z-20 p-1.5 flex flex-col gap-1">
                        <div class="h-[5px] rounded-sm w-[40%] bg-slate-300"></div>
                        <div class="h-[5px] rounded-sm w-[90%] bg-[#eaeaea]"></div>
                        <div class="h-[5px] rounded-sm w-[75%] bg-blue-500/40 ml-2.5"></div>
                        <div class="h-[5px] rounded-sm w-[60%] bg-emerald-500/40 ml-2.5"></div>
                    </div>
                    <div
                        class="w-[28px] h-[24px] bg-slate-300 mt-0.5 z-10 [clip-path:polygon(25%_0,75%_0,100%_100%,0%_100%)]">
                    </div>
                    <div class="w-[60px] h-[5px] bg-slate-400 rounded-t-[3px]"></div>
                </div>

                <div class="absolute w-[75px] h-[75px] bottom-[86px] z-[60] flex justify-center items-center">
                    <img src="https://picsum.photos/150?random=1" alt="Avatar"
                        class="w-full h-full rounded-full object-cover shadow-[0_2px_5px_rgba(0,0,0,0.15)] bg-slate-100 transition-transform duration-300 group-hover:scale-[1.08]">
                </div>

                <div class="absolute w-full h-[140px] bottom-0 z-20">
                    <svg width="100%" height="100%" viewBox="0 0 340 140" xmlns="http://www.w3.org/2000/svg">
                        <rect x="10" y="0" width="320" height="8" rx="2" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="2" />
                        <line x1="25" y1="8" x2="25" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <line x1="315" y1="8" x2="315" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <rect x="230" y="8" width="65" height="100" fill="#ffffff" stroke="#e2e8f0" stroke-width="2" />
                        <line x1="230" y1="42" x2="295" y2="42" stroke="#e2e8f0" stroke-width="1.5" />
                        <line x1="230" y1="74" x2="295" y2="74" stroke="#e2e8f0" stroke-width="1.5" />
                        <circle cx="262" cy="25" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="58" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="90" r="3" fill="#cbd5e1" />
                    </svg>
                </div>

                <div class="absolute w-[142px] h-[188px] -bottom-[5px] z-50 pointer-events-none">
                    <svg width="100%" height="100%" viewBox="0 0 100 130" preserveAspectRatio="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <ellipse cx="50" cy="85" rx="30" ry="8" fill="#f1f5f9" />
                        <rect x="18" y="10" width="64" height="65" rx="16" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="3" />
                        <path
                            d="M 12 75 C 12 70 20 68 50 68 C 80 68 88 70 88 75 C 88 84 75 88 50 88 C 20 88 12 84 12 75 Z"
                            fill="#ffffff" stroke="#e2e8f0" stroke-width="2.5" />
                        <line x1="50" y1="88" x2="50" y2="112" stroke="#94a3b8" stroke-width="5" />
                        <path
                            d="M 50 112 L 25 124 M 50 112 L 75 124 M 50 112 L 50 128 M 50 112 L 32 116 M 50 112 L 68 116"
                            stroke="#cbd5e1" stroke-width="4" stroke-linecap="round" />
                        <circle cx="25" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="75" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="50" cy="129" r="3.5" fill="#64748b" />
                    </svg>
                </div>
            </div>

            <div
                class="group relative w-[340px] h-[280px] flex flex-col items-center justify-end transition-transform duration-400 hover:-translate-y-1.5">
                <div
                    class="absolute -bottom-2.5 w-[280px] h-[20px] bg-[radial-gradient(ellipse_at_center,rgba(0,0,0,0.06)_0%,rgba(0,0,0,0)_70%)] z-10 pointer-events-none">
                </div>

                <div class="absolute w-[160px] h-[120px] bottom-[155px] z-30 flex flex-col items-center justify-start">
                    <div
                        class="w-[160px] h-[94px] rounded border-[3px] border-[#66a3ff] bg-slate-50 flex items-end p-2 overflow-hidden relative shadow-[0_4px_10px_rgba(0,0,0,0.05)] z-20">
                        <svg width="100%" height="100%" viewBox="0 0 140 84" xmlns="http://www.w3.org/2000/svg">
                            <path d="M 10 70 Q 40 20 70 50 T 130 15" fill="none" stroke="#ef4444" stroke-width="2.5" />
                            <path d="M 10 55 Q 35 60 70 30 T 130 40" fill="none" stroke="#22c55e" stroke-width="1.5" />
                            <path d="M 10 40 Q 45 10 80 65 T 130 30" fill="none" stroke="#3b82f6" stroke-width="1.5" />
                        </svg>
                    </div>
                    <div
                        class="w-[28px] h-[24px] bg-slate-300 mt-0.5 z-10 [clip-path:polygon(25%_0,75%_0,100%_100%,0%_100%)]">
                    </div>
                    <div class="w-[60px] h-[5px] bg-slate-400 rounded-t-[3px]"></div>
                </div>

                <div class="absolute w-[75px] h-[75px] bottom-[86px] z-[60] flex justify-center items-center">
                    <img src="https://picsum.photos/150?random=2" alt="Avatar"
                        class="w-full h-full rounded-full object-cover shadow-[0_2px_5px_rgba(0,0,0,0.15)] bg-slate-100 transition-transform duration-300 group-hover:scale-[1.08]">
                </div>

                <div class="absolute w-full h-[140px] bottom-0 z-20">
                    <svg width="100%" height="100%" viewBox="0 0 340 140" xmlns="http://www.w3.org/2000/svg">
                        <rect x="10" y="0" width="320" height="8" rx="2" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="2" />
                        <line x1="25" y1="8" x2="25" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <line x1="315" y1="8" x2="315" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <rect x="230" y="8" width="65" height="100" fill="#ffffff" stroke="#e2e8f0" stroke-width="2" />
                        <line x1="230" y1="42" x2="295" y2="42" stroke="#e2e8f0" stroke-width="1.5" />
                        <line x1="230" y1="74" x2="295" y2="74" stroke="#e2e8f0" stroke-width="1.5" />
                        <circle cx="262" cy="25" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="58" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="90" r="3" fill="#cbd5e1" />
                    </svg>
                </div>

                <div class="absolute w-[142px] h-[188px] -bottom-[5px] z-50 pointer-events-none">
                    <svg width="100%" height="100%" viewBox="0 0 100 130" preserveAspectRatio="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <ellipse cx="50" cy="85" rx="30" ry="8" fill="#f1f5f9" />
                        <rect x="18" y="10" width="64" height="65" rx="16" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="3" />
                        <path
                            d="M 12 75 C 12 70 20 68 50 68 C 80 68 88 70 88 75 C 88 84 75 88 50 88 C 20 88 12 84 12 75 Z"
                            fill="#ffffff" stroke="#e2e8f0" stroke-width="2.5" />
                        <line x1="50" y1="88" x2="50" y2="112" stroke="#94a3b8" stroke-width="5" />
                        <path
                            d="M 50 112 L 25 124 M 50 112 L 75 124 M 50 112 L 50 128 M 50 112 L 32 116 M 50 112 L 68 116"
                            stroke="#cbd5e1" stroke-width="4" stroke-linecap="round" />
                        <circle cx="25" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="75" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="50" cy="129" r="3.5" fill="#64748b" />
                    </svg>
                </div>
            </div>
        </div>

        <div
            class="grid grid-cols-2 gap-x-[40px] gap-y-[40px] bg-slate-50/50 p-6 rounded-2xl border-2 border-slate-200/50 shadow-sm">

            <div
                class="group relative w-[340px] h-[280px] flex flex-col items-center justify-end transition-transform duration-400 hover:-translate-y-1.5">
                <div
                    class="absolute -bottom-2.5 w-[280px] h-[20px] bg-[radial-gradient(ellipse_at_center,rgba(0,0,0,0.06)_0%,rgba(0,0,0,0)_70%)] z-10 pointer-events-none">
                </div>

                <div class="absolute w-[160px] h-[120px] bottom-[155px] z-30 flex flex-col items-center justify-start">
                    <div
                        class="w-[160px] h-[94px] rounded border-[3px] border-[#66a3ff] bg-gray-900 flex justify-center items-center overflow-hidden relative shadow-[0_4px_10px_rgba(0,0,0,0.05)] z-20">
                        <svg width="40" height="40" viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg">
                            <ellipse cx="20" cy="24" rx="12" ry="14" fill="#000000" />
                            <ellipse cx="20" cy="25" rx="8" ry="11" fill="#ffffff" />
                            <circle cx="20" cy="12" r="7" fill="#000000" />
                            <circle cx="18" cy="11" r="1.5" fill="#ffffff" />
                            <circle cx="18" cy="11" r="0.7" fill="#000000" />
                            <circle cx="22" cy="11" r="1.5" fill="#ffffff" />
                            <circle cx="22" cy="11" r="0.7" fill="#000000" />
                            <polygon points="17,13 23,13 20,17" fill="#f97316" />
                        </svg>
                    </div>
                    <div
                        class="w-[28px] h-[24px] bg-slate-300 mt-0.5 z-10 [clip-path:polygon(25%_0,75%_0,100%_100%,0%_100%)]">
                    </div>
                    <div class="w-[60px] h-[5px] bg-slate-400 rounded-t-[3px]"></div>
                </div>

                <div class="absolute w-[75px] h-[75px] bottom-[86px] z-[60] flex justify-center items-center">
                    <img src="https://picsum.photos/150?random=3" alt="Avatar"
                        class="w-full h-full rounded-full object-cover shadow-[0_2px_5px_rgba(0,0,0,0.15)] bg-slate-100 transition-transform duration-300 group-hover:scale-[1.08]">
                </div>

                <div class="absolute w-full h-[140px] bottom-0 z-20">
                    <svg width="100%" height="100%" viewBox="0 0 340 140" xmlns="http://www.w3.org/2000/svg">
                        <rect x="10" y="0" width="320" height="8" rx="2" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="2" />
                        <line x1="25" y1="8" x2="25" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <line x1="315" y1="8" x2="315" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <rect x="230" y="8" width="65" height="100" fill="#ffffff" stroke="#e2e8f0" stroke-width="2" />
                        <line x1="230" y1="42" x2="295" y2="42" stroke="#e2e8f0" stroke-width="1.5" />
                        <line x1="230" y1="74" x2="295" y2="74" stroke="#e2e8f0" stroke-width="1.5" />
                        <circle cx="262" cy="25" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="58" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="90" r="3" fill="#cbd5e1" />
                    </svg>
                </div>

                <div class="absolute w-[142px] h-[188px] -bottom-[5px] z-50 pointer-events-none">
                    <svg width="100%" height="100%" viewBox="0 0 100 130" preserveAspectRatio="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <ellipse cx="50" cy="85" rx="30" ry="8" fill="#f1f5f9" />
                        <rect x="18" y="10" width="64" height="65" rx="16" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="3" />
                        <path
                            d="M 12 75 C 12 70 20 68 50 68 C 80 68 88 70 88 75 C 88 84 75 88 50 88 C 20 88 12 84 12 75 Z"
                            fill="#ffffff" stroke="#e2e8f0" stroke-width="2.5" />
                        <line x1="50" y1="88" x2="50" y2="112" stroke="#94a3b8" stroke-width="5" />
                        <path
                            d="M 50 112 L 25 124 M 50 112 L 75 124 M 50 112 L 50 128 M 50 112 L 32 116 M 50 112 L 68 116"
                            stroke="#cbd5e1" stroke-width="4" stroke-linecap="round" />
                        <circle cx="25" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="75" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="50" cy="129" r="3.5" fill="#64748b" />
                    </svg>
                </div>
            </div>

            <div
                class="group relative w-[340px] h-[280px] flex flex-col items-center justify-end transition-transform duration-400 hover:-translate-y-1.5">
                <div
                    class="absolute -bottom-2.5 w-[280px] h-[20px] bg-[radial-gradient(ellipse_at_center,rgba(0,0,0,0.06)_0%,rgba(0,0,0,0)_70%)] z-10 pointer-events-none">
                </div>

                <div class="absolute top-[50px] left-[75px] z-[100] pointer-events-none">
                    <div class="zzz zzz-1">z</div>
                    <div class="zzz zzz-2">Z</div>
                    <div class="zzz zzz-3">zZ</div>
                </div>

                <div class="absolute w-[160px] h-[120px] bottom-[155px] z-30 flex flex-col items-center justify-start">
                    <div
                        class="w-[160px] h-[94px] rounded border-[3px] border-[#66a3ff] bg-[#1a1a1a] overflow-hidden relative shadow-[0_4px_10px_rgba(0,0,0,0.05)] z-20">
                    </div>
                    <div
                        class="w-[28px] h-[24px] bg-slate-300 mt-0.5 z-10 [clip-path:polygon(25%_0,75%_0,100%_100%,0%_100%)]">
                    </div>
                    <div class="w-[60px] h-[5px] bg-slate-400 rounded-t-[3px]"></div>
                </div>

                <div class="absolute w-[75px] h-[75px] bottom-[86px] z-[60] flex justify-center items-center">
                    <img src="https://picsum.photos/150?random=4" alt="Avatar"
                        class="w-full h-full rounded-full object-cover shadow-[0_2px_5px_rgba(0,0,0,0.15)] bg-slate-100 transition-transform duration-300 group-hover:scale-[1.08] brightness-75">
                </div>

                <div class="absolute w-full h-[140px] bottom-0 z-20">
                    <svg width="100%" height="100%" viewBox="0 0 340 140" xmlns="http://www.w3.org/2000/svg">
                        <rect x="10" y="0" width="320" height="8" rx="2" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="2" />
                        <line x1="25" y1="8" x2="25" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <line x1="315" y1="8" x2="315" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <rect x="230" y="8" width="65" height="100" fill="#ffffff" stroke="#e2e8f0" stroke-width="2" />
                        <line x1="230" y1="42" x2="295" y2="42" stroke="#e2e8f0" stroke-width="1.5" />
                        <line x1="230" y1="74" x2="295" y2="74" stroke="#e2e8f0" stroke-width="1.5" />
                        <circle cx="262" cy="25" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="58" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="90" r="3" fill="#cbd5e1" />
                    </svg>
                </div>

                <div class="absolute w-[142px] h-[188px] -bottom-[5px] z-50 pointer-events-none">
                    <svg width="100%" height="100%" viewBox="0 0 100 130" preserveAspectRatio="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <ellipse cx="50" cy="85" rx="30" ry="8" fill="#f1f5f9" />
                        <rect x="18" y="10" width="64" height="65" rx="16" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="3" />
                        <path
                            d="M 12 75 C 12 70 20 68 50 68 C 80 68 88 70 88 75 C 88 84 75 88 50 88 C 20 88 12 84 12 75 Z"
                            fill="#ffffff" stroke="#e2e8f0" stroke-width="2.5" />
                        <line x1="50" y1="88" x2="50" y2="112" stroke="#94a3b8" stroke-width="5" />
                        <path
                            d="M 50 112 L 25 124 M 50 112 L 75 124 M 50 112 L 50 128 M 50 112 L 32 116 M 50 112 L 68 116"
                            stroke="#cbd5e1" stroke-width="4" stroke-linecap="round" />
                        <circle cx="25" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="75" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="50" cy="129" r="3.5" fill="#64748b" />
                    </svg>
                </div>
            </div>

            <div
                class="group relative w-[340px] h-[280px] flex flex-col items-center justify-end transition-transform duration-400 hover:-translate-y-1.5">
                <div
                    class="absolute -bottom-2.5 w-[280px] h-[20px] bg-[radial-gradient(ellipse_at_center,rgba(0,0,0,0.06)_0%,rgba(0,0,0,0)_70%)] z-10 pointer-events-none">
                </div>

                <div class="absolute w-[160px] h-[120px] bottom-[155px] z-30 flex flex-col items-center justify-start">
                    <div
                        class="w-[160px] h-[94px] rounded border-[3px] border-[#66a3ff] bg-blue-50 flex justify-around items-center p-1 overflow-hidden relative shadow-[0_4px_10px_rgba(0,0,0,0.05)] z-20">
                        <div
                            class="w-[36px] h-[72px] bg-white border border-gray-300 rounded-[3px] p-0.5 flex flex-col gap-0.5">
                            <div class="h-[35px] bg-red-300 rounded-[1px]"></div>
                        </div>
                        <div
                            class="w-[36px] h-[72px] bg-white border border-gray-300 rounded-[3px] p-0.5 flex flex-col gap-0.5">
                            <div class="h-[35px] bg-blue-300 rounded-[1px]"></div>
                        </div>
                    </div>
                    <div
                        class="w-[28px] h-[24px] bg-slate-300 mt-0.5 z-10 [clip-path:polygon(25%_0,75%_0,100%_100%,0%_100%)]">
                    </div>
                    <div class="w-[60px] h-[5px] bg-slate-400 rounded-t-[3px]"></div>
                </div>

                <div class="absolute w-[75px] h-[75px] bottom-[86px] z-[60] flex justify-center items-center">
                    <img src="https://picsum.photos/150?random=5" alt="Avatar"
                        class="w-full h-full rounded-full object-cover shadow-[0_2px_5px_rgba(0,0,0,0.15)] bg-slate-100 transition-transform duration-300 group-hover:scale-[1.08]">
                </div>

                <div class="absolute w-full h-[140px] bottom-0 z-20">
                    <svg width="100%" height="100%" viewBox="0 0 340 140" xmlns="http://www.w3.org/2000/svg">
                        <rect x="10" y="0" width="320" height="8" rx="2" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="2" />
                        <line x1="25" y1="8" x2="25" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <line x1="315" y1="8" x2="315" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <rect x="230" y="8" width="65" height="100" fill="#ffffff" stroke="#e2e8f0" stroke-width="2" />
                        <line x1="230" y1="42" x2="295" y2="42" stroke="#e2e8f0" stroke-width="1.5" />
                        <line x1="230" y1="74" x2="295" y2="74" stroke="#e2e8f0" stroke-width="1.5" />
                        <circle cx="262" cy="25" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="58" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="90" r="3" fill="#cbd5e1" />
                    </svg>
                </div>

                <div class="absolute w-[142px] h-[188px] -bottom-[5px] z-50 pointer-events-none">
                    <svg width="100%" height="100%" viewBox="0 0 100 130" preserveAspectRatio="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <ellipse cx="50" cy="85" rx="30" ry="8" fill="#f1f5f9" />
                        <rect x="18" y="10" width="64" height="65" rx="16" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="3" />
                        <path
                            d="M 12 75 C 12 70 20 68 50 68 C 80 68 88 70 88 75 C 88 84 75 88 50 88 C 20 88 12 84 12 75 Z"
                            fill="#ffffff" stroke="#e2e8f0" stroke-width="2.5" />
                        <line x1="50" y1="88" x2="50" y2="112" stroke="#94a3b8" stroke-width="5" />
                        <path
                            d="M 50 112 L 25 124 M 50 112 L 75 124 M 50 112 L 50 128 M 50 112 L 32 116 M 50 112 L 68 116"
                            stroke="#cbd5e1" stroke-width="4" stroke-linecap="round" />
                        <circle cx="25" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="75" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="50" cy="129" r="3.5" fill="#64748b" />
                    </svg>
                </div>
            </div>

            <div
                class="group relative w-[340px] h-[280px] flex flex-col items-center justify-end transition-transform duration-400 hover:-translate-y-1.5">
                <div
                    class="absolute -bottom-2.5 w-[280px] h-[20px] bg-[radial-gradient(ellipse_at_center,rgba(0,0,0,0.06)_0%,rgba(0,0,0,0)_70%)] z-10 pointer-events-none">
                </div>

                <div class="absolute w-[160px] h-[120px] bottom-[155px] z-30 flex flex-col items-center justify-start">
                    <div
                        class="w-[160px] h-[94px] rounded border-[3px] border-[#66a3ff] bg-white flex flex-col items-center justify-center p-2 overflow-hidden relative shadow-[0_4px_10px_rgba(0,0,0,0.05)] z-20">
                        <div class="text-[8px] font-bold text-blue-500 mb-1.5">Google</div>
                        <div class="w-[90%] h-[14px] border border-gray-200 rounded-full bg-gray-50"></div>
                    </div>
                    <div
                        class="w-[28px] h-[24px] bg-slate-300 mt-0.5 z-10 [clip-path:polygon(25%_0,75%_0,100%_100%,0%_100%)]">
                    </div>
                    <div class="w-[60px] h-[5px] bg-slate-400 rounded-t-[3px]"></div>
                </div>

                <div class="absolute w-[75px] h-[75px] bottom-[86px] z-[60] flex justify-center items-center">
                    <img src="https://picsum.photos/150?random=6" alt="Avatar"
                        class="w-full h-full rounded-full object-cover shadow-[0_2px_5px_rgba(0,0,0,0.15)] bg-slate-100 transition-transform duration-300 group-hover:scale-[1.08]">
                </div>

                <div class="absolute w-full h-[140px] bottom-0 z-20">
                    <svg width="100%" height="100%" viewBox="0 0 340 140" xmlns="http://www.w3.org/2000/svg">
                        <rect x="10" y="0" width="320" height="8" rx="2" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="2" />
                        <line x1="25" y1="8" x2="25" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <line x1="315" y1="8" x2="315" y2="140" stroke="#cbd5e1" stroke-width="3.5" />
                        <rect x="230" y="8" width="65" height="100" fill="#ffffff" stroke="#e2e8f0" stroke-width="2" />
                        <line x1="230" y1="42" x2="295" y2="42" stroke="#e2e8f0" stroke-width="1.5" />
                        <line x1="230" y1="74" x2="295" y2="74" stroke="#e2e8f0" stroke-width="1.5" />
                        <circle cx="262" cy="25" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="58" r="3" fill="#cbd5e1" />
                        <circle cx="262" cy="90" r="3" fill="#cbd5e1" />
                    </svg>
                </div>

                <div class="absolute w-[142px] h-[188px] -bottom-[5px] z-50 pointer-events-none">
                    <svg width="100%" height="100%" viewBox="0 0 100 130" preserveAspectRatio="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <ellipse cx="50" cy="85" rx="30" ry="8" fill="#f1f5f9" />
                        <rect x="18" y="10" width="64" height="65" rx="16" fill="#ffffff" stroke="#e2e8f0"
                            stroke-width="3" />
                        <path
                            d="M 12 75 C 12 70 20 68 50 68 C 80 68 88 70 88 75 C 88 84 75 88 50 88 C 20 88 12 84 12 75 Z"
                            fill="#ffffff" stroke="#e2e8f0" stroke-width="2.5" />
                        <line x1="50" y1="88" x2="50" y2="112" stroke="#94a3b8" stroke-width="5" />
                        <path
                            d="M 50 112 L 25 124 M 50 112 L 75 124 M 50 112 L 50 128 M 50 112 L 32 116 M 50 112 L 68 116"
                            stroke="#cbd5e1" stroke-width="4" stroke-linecap="round" />
                        <circle cx="25" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="75" cy="125" r="3.5" fill="#64748b" />
                        <circle cx="50" cy="129" r="3.5" fill="#64748b" />
                    </svg>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.zzz {
    position: absolute;
    font-weight: bold;
    color: gray;
    opacity: 0;
    animation: floatSleep 3s infinite linear;
}

.zzz-1 {
    animation-delay: 0s;
    left: 0px;
    font-size: 12px;
}

.zzz-2 {
    animation-delay: 1s;
    left: 15px;
    font-size: 15px;
}

.zzz-3 {
    animation-delay: 2s;
    left: 5px;
    font-size: 18px;
}

@keyframes floatSleep {
    0% {
        transform: translate(0, 0) scale(0.9);
        opacity: 0;
    }

    20% {
        opacity: 0.8;
    }

    80% {
        opacity: 0.4;
    }

    100% {
        transform: translate(20px, -50px) scale(1.2);
        opacity: 0;
    }
}
</style>