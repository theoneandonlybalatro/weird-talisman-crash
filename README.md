# weird-talisman-crash
so booting up balatro with the talisman folder in the mods folder 
ot gives me the error msg
(8) Lua method 'start_up' at file 'main.lua:2181'
        Local variables:
         self = table: 0x2781c638  {F_GUIDE:false, F_CRASH_REPORTS:false, F_QUIT_BUTTON:true, F_ENGLISH_ONLY:false, F_VIDEO_SETTINGS:true, STAGE:1, F_MOBILE_UI:false, F_NO_SAVING:false (more...)}
(9) Lua field 'load' at file 'main.lua:948'
(10) Lua function '?' at file 'main.lua:895' (best guess)
(11) global C function 'xpcall'
(12) LÖVE function at file 'boot.lua:368' (best guess)
        Local variables:
         result = boolean: true
         main = nil
(13) global C function 'xpcall'
(14) LÖVE function at file 'boot.lua:377' (best guess)
        Local variables:
         func = Lua function '(LÖVE Function)' (defined at line 355 of chunk [love "boot.lua"])
         inerror = boolean: true
         deferErrhand = Lua function '(LÖVE Function)' (defined at line 348 of chunk [love "boot.lua"])
         earlyinit = Lua function '(LÖVE Function)' (defined at line 355 of chunk [love "boot.lua"])

INFO - [G] file not found: main.lua: No such file or directory
INFO - [G] 2025-08-12 22:21:28 :: INFO  :: StackTrace :: Additional Context:
Balatro Version: 1.0.1o-FULL
Modded Version: 1.0.0~BETA-0810a-STEAMODDED
LÖVE Version: 11.5.0
Lovely Version: 0.8.0
Platform: Windows
Steamodded Mods:
    1: Talisman by MathIsFun_, Mathguy24, jenwalter666, cg-223, lord.ruby [ID: Talisman, Version: 2.3.4, Uses Lovely]
        Break Infinity: omeganum
    2: Cryptid by MathIsFun_, Cryptid and Balatro Discords [ID: Cryptid, Priority: 114, Version: 0.5.12~dev]
  
