--[[
  _______ _    _ ______   __  __ _____ __  __ _____ _____       __   ___ ____         _  _     __ ___   __   ___   
 |__   __| |  | |  ____| |  \/  |_   _|  \/  |_   _/ ____|     / /  / _ \___ \      _| || |_  / /|__ \ / /  / _ \  
    | |  | |__| | |__    | \  / | | | | \  / | | || |         / /  | | | |__) | ___|_  __  _|/ /_   ) / /_ | | | | 
    | |  |  __  |  __|   | |\/| | | | | |\/| | | || |        / /   | | | |__ < / __|_| || |_| '_ \ / / '_ \| | | | 
    | |  | |  | | |____  | |  | |_| |_| |  | |_| || |____   / /    | |_| |__) |\__ \_  __  _| (_) / /| (_) | |_| | 
   _|_|_ |_|  |_|______| |_|  |_|_____|_|  |_|_____\_____| /_/______\___/____(_)___/ |_||_|  \___/____\___/ \___/  
  / ____|         (_)     | |    / ____| | (_) | | (_)       |__   __|      | | (_)                                
 | (___   ___ _ __ _ _ __ | |_  | (___ | |_ _| | |  _ _ __      | | ___  ___| |_ _ _ __   __ _                     
  \___ \ / __| '__| | '_ \| __|  \___ \| __| | | | | | '_ \     | |/ _ \/ __| __| | '_ \ / _` |                    
  ____) | (__| |  | | |_) | |_   ____) | |_| | | | | | | | |    | |  __/\__ \ |_| | | | | (_| |                    
 |_____/ \___|_|  |_| .__/ \__| |_____/ \__|_|_|_| |_|_| |_|    |_|\___||___/\__|_|_| |_|\__, |                    
                    | |                                                                   __/ |                    
                    |_|                                                                  |___/  
                    
                    Creator = 03.s#6260
                    
--]]

do local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function()return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...)local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30)if (v1(v30,2)==79) then local v70=0;while true do if (0==v70) then v19=v0(v3(v30,1,1));return "";end end else local v71=v2(v0(v30,16));if v19 then local v78=0;local v79;while true do if (v78==1) then return v79;end if (v78==0) then v79=v5(v71,v19);v19=nil;v78=1;end end else return v71;end end end);local function v20(v31,v32,v33)if v33 then local v72=0 -0 ;local v73;while true do if (v72==0) then v73=(v31/((2 + 0)^(v32-(1 + 0 + 0))))%((4 -2)^(((v33-(1 -0)) -(v32-1)) + 1 + 0)) ;return v73-(v73%(491 -(155 + 335))) ;end end else local v74=(3 -1)^(v32-((1 + 0) -0)) ;return (((v31%(v74 + v74))>=v74) and (1 + 0)) or (1029 -(922 + 107)) ;end end local function v21()local v34=0 -0 ;local v35;while true do if (v34==(1 + 0 + 0)) then return v35;end if (v34==(0 -0)) then v35=v1(v16,v18,v18);v18=v18 + 1 ;v34=1 + 0 ;end end end local function v22()local v36=121 -(84 + 37) ;local v37;local v38;while true do if ((1086 -(325 + 761))==v36) then v37,v38=v1(v16,v18,v18 + 1 + 1 );v18=v18 + (2 -(0 + 0)) ;v36=1 -0 ;end if (v36==(350 -(46 + 303))) then return (v38 * (191 + 65)) + v37 ;end end end local function v23()local v39=0 -0 ;local v40;local v41;local v42;local v43;while true do if (v39==((1536 -(1430 + 105)) -0)) then return (v43 * ((11504672 -(594 + 304)) + 5273442)) + (v42 * (4904 + 60632)) + (v41 * (665 -(98 + 311))) + v40 ;end if (v39==0) then v40,v41,v42,v43=v1(v16,v18,v18 + (8 -5) );v18=v18 + (10 -6) ;v39=3 -(2 + 0) ;end end end local function v24()local v44=v23();local v45=v23();local v46=3 -2 ;local v47=(v20(v45,1 -0 ,445 -(130 + (1213 -(689 + 229))) ) * (2^32)) + v44 ;local v48=v20(v45,725 -(262 + 442) ,746 -(485 + 230) );local v49=((v20(v45,25 + 7 )==1) and  -(4 -3)) or (1 + 0) ;if (v48==(0 -0)) then if (v47==(0 + (0 -0))) then return v49 * 0 ;else local v80=(436 + 1154) -(492 + 1098) ;while true do if (v80==(0 + 0)) then v48=(1705 -(1557 + 147)) + 0 ;v46=0 + 0 ;break;end end end elseif (v48==(1301 + 746)) then return ((v47==0) and (v49 * (1/(0 -0)))) or (v49 * NaN) ;end return v8(v49,v48-(1571 -548) ) * (v46 + (v47/((1 + 1)^(205 -153)))) ;end local function v25(v50)local v51=377 -(196 + 181) ;local v52;local v53;while true do if (v51==((3 + 0) -0)) then return v6(v53);end if (v51==((0 -0) -0)) then v52=nil;if  not v50 then local v88=727 -(284 + 416 + 27) ;while true do if (v88==(0 + 0)) then v50=v23();if (v50==((3469 -(1229 + 641)) -(1198 + 401))) then return "";end break;end end end v51=1;end if (v51==(7 -5)) then v53={};for v81=1 -0 , #v52 do v53[v81]=v2(v1(v3(v52,v81,v81)));end v51=3 + (1878 -(250 + 1628)) ;end if (v51==(1251 -(456 + 794))) then v52=v3(v16,v18,(v18 + v50) -(1 + 0) );v18=v18 + v50 ;v51=(1654 -(1243 + 410)) + 1 ;end end end local v26=v23;local function v27(...)return {...},v12("#",...);end local function v28()local v54=850 -(658 + 192) ;local v55;local v56;local v57;local v58;local v59;local v60;local v61;local v62;while true do if (v54==3) then v61=nil;v62=nil;v54=4 + 0 ;end if (v54==(1704 -(834 + 866))) then while true do if (v55==3) then v62=nil;while true do local v106=0;while true do if ((1054 -(139 + 915))==v106) then if (v56~=2) then else for v115=2 -1 ,v23() do local v116=0;local v117;local v118;while true do if (0==v116) then v117=0;v118=nil;v116=1 + 0 ;end if ((1043 -(983 + 59))==v116) then while true do if (v117~=(0 -0)) then else v118=v21();if (v20(v118,1,1)==0) then local v150=0;local v151;local v152;local v153;local v154;local v155;while true do if (v150==0) then v151=0;v152=nil;v150=82 -(21 + 60) ;end if (v150~=(5 -3)) then else v155=nil;while true do if (v151==(1 + 0)) then v154=nil;v155=nil;v151=2;end if (2~=v151) then else while true do if (v152==(322 -(120 + 201))) then local v208=0 + 0 ;while true do if (v208==1) then v152=2;break;end if (v208~=(0 + 0)) then else v155={v22(),v22(),nil,nil};if (v153==(0 -0)) then local v224=0 + 0 ;local v225;local v226;while true do if (v224==(1 + 0)) then while true do if (v225~=0) then else v226=0;while true do if (v226==(0 -0)) then v155[3]=v22();v155[4]=v22();break;end end break;end end break;end if (v224==0) then v225=0;v226=nil;v224=211 -(126 + 84) ;end end elseif (v153==1) then v155[3]=v23();elseif (v153==(1754 -(1372 + 380))) then v155[3]=v23() -((5 -3)^(15 + 1)) ;elseif (v153~=(1596 -(776 + 817))) then else local v235=1504 -(375 + 1129) ;local v236;local v237;local v238;while true do if (v235==(1940 -(1076 + 863))) then v238=nil;while true do if ((0 + 0)==v236) then v237=0 -0 ;v238=nil;v236=362 -(38 + 323) ;end if (v236==(1956 -(1340 + 615))) then while true do if (v237==(0 + 0)) then v238=0 -0 ;while true do if (v238==(241 -(65 + 176))) then v155[3]=v23() -(2^(37 -21)) ;v155[4]=v22();break;end end break;end end break;end end break;end if (v235==(0 -0)) then v236=502 -(6 + 496) ;v237=nil;v235=1;end end end v208=1006 -(243 + 762) ;end end end if (v152~=(429 -(10 + 417))) then else local v209=0 -0 ;local v210;while true do if (v209~=(589 -(303 + 286))) then else v210=0 -0 ;while true do if ((640 -(191 + 448))==v210) then v152=3;break;end if ((1297 -(1240 + 57))==v210) then local v229=0;while true do if (v229==(0 -0)) then if (v20(v154,1,1)~=(2 -1)) then else v155[2]=v62[v155[8 -6 ]];end if (v20(v154,1198 -(1141 + 55) ,2)==(220 -(89 + 130))) then v155[2 + 1 ]=v62[v155[3]];end v229=1;end if (v229==1) then v210=1;break;end end end end break;end end end if (v152==0) then local v211=0 -0 ;local v212;while true do if (v211~=0) then else v212=0;while true do if (v212~=(0 + 0)) then else v153=v20(v118,2,1034 -(338 + 693) );v154=v20(v118,4,6);v212=1 + 0 ;end if (v212~=1) then else v152=1;break;end end break;end end end if (v152==3) then if (v20(v154,3,11 -8 )~=(1698 -(687 + 1010))) then else v155[1243 -(563 + 676) ]=v62[v155[4]];end v57[v115]=v155;break;end end break;end if (0==v151) then v152=0;v153=nil;v151=1;end end break;end if (v150~=(1 + 0)) then else v153=nil;v154=nil;v150=1207 -(466 + 739) ;end end end break;end end break;end end end for v119=1 -0 ,v23() do v58[v119-1 ]=v28();end for v121=1,v23() do v59[v121]=v23();end return v60;end if (1~=v56) then else v61=v23();v62={};for v123=1,v61 do local v124=0 -0 ;local v125;local v126;local v127;local v128;local v129;while true do if (v124~=2) then else v129=nil;while true do if (v125==2) then while true do if (v126==1) then v129=nil;while true do if (v127~=1) then else if (v128==(1 + 0)) then v129=v21()~=(0 -0) ;elseif (v128==(1 + 1)) then v129=v24();elseif (v128==(7 -4)) then v129=v25();end v62[v123]=v129;break;end if (v127~=0) then else local v193=0;local v194;while true do if (v193==(0 + 0)) then v194=0;while true do if (v194==1) then v127=1 + 0 ;break;end if (v194==0) then local v214=0;while true do if (v214==(1 + 0)) then v194=1;break;end if (v214==(0 -0)) then v128=v21();v129=nil;v214=1;end end end end break;end end end end break;end if (v126~=0) then else local v156=0;while true do if (v156~=(0 + 0)) then else v127=1897 -(1789 + 108) ;v128=nil;v156=928 -(93 + 834) ;end if (v156==(2 -1)) then v126=1;break;end end end end break;end if (0==v125) then v126=0 -0 ;v127=nil;v125=1131 -(896 + 234) ;end if (v125==1) then v128=nil;v129=nil;v125=1319 -(764 + 553) ;end end break;end if (v124==(1070 -(989 + 80))) then v127=nil;v128=nil;v124=2;end if (v124~=(0 -0)) then else v125=1890 -(600 + 1290) ;v126=nil;v124=441 -(187 + 253) ;end end end v60[3]=v21();v56=1 + 1 ;end v106=1 -0 ;end if (1==v106) then if (v56==(533 -(443 + 90))) then local v112=892 -(102 + 790) ;while true do if (v112==(1972 -(1213 + 758))) then v59={};v60={v57,v58,nil,v59};v112=5 -3 ;end if (v112==(2 + 0)) then v56=1532 -(1096 + 435) ;break;end if (v112~=(0 + 0)) then else local v130=0;while true do if (v130==(1504 -(253 + 1250))) then v112=1 + 0 ;break;end if (v130==(0 + 0)) then v57={};v58={};v130=1 + 0 ;end end end end end break;end end end break;end if (v55~=2) then else local v99=0;while true do if (v99==0) then v60=nil;v61=nil;v99=1;end if (v99~=(555 -(425 + 129))) then else v55=3;break;end end end if (v55==(1 + 0)) then local v100=0 -0 ;while true do if (v100~=(0 -0)) then else v58=nil;v59=nil;v100=1;end if (v100==1) then v55=2 -0 ;break;end end end if (v55==0) then local v101=249 -(244 + 5) ;while true do if (v101~=(0 -0)) then else v56=0;v57=nil;v101=1441 -(1025 + 415) ;end if (v101~=(491 -(324 + 166))) then else v55=4 -3 ;break;end end end end break;end if (v54==1) then v57=nil;v58=nil;v54=2;end if (v54==(4 -2)) then v59=nil;v60=nil;v54=1 + 2 ;end if (v54==(0 + 0)) then v55=0;v56=nil;v54=3 -2 ;end end end local function v29(v63,v64,v65)local v66=0;local v67;local v68;local v69;while true do if (v66==1) then v69=v63[3];return function(...)local v83=1;local v84= -1;local v85={...};local v86=v12("#",...) -1 ;local function v87()local v89=v67;local v90=v68;local v91=v69;local v92=v27;local v93={};local v94={};local v95={};for v102=0 + 0 ,v86 do if ((v102>=v91) or ((6422 -3193)<=(2108 -(541 + 772 + 81)))) then v93[v102-v91 ]=v85[v102 + 1 + 0 ];else v95[v102]=v85[v102 + 1 + 0 ];end end local v96=(v86-v91) + (1328 -(905 + 422)) + 0 ;local v97;local v98;while true do local v103=0 -(0 -0) ;local v104;while true do if (((2262 -(41 + 277))<=(4273 + 153 + 3)) and (v103==(0 + 0))) then v104=0 -0 ;while true do if ((((4894 + 858) -(782 + 331))==(15480 -10841)) and (((1009 -(55 + 954)) + 0)==v104)) then local v113=559 -((227 -121) + 453) ;local v114;while true do if (((4958 -(203 + 772))>=(3503 -959)) and (v113==0)) then v114=0 -0 ;while true do if ((((6289 -2384) -(256 + 1272))>=(1245 -838)) and ((66 -((654 -(252 + 351)) + 14))==v114)) then v104=1876 -(1486 + 389) ;break;end if ((v114==(0 + 0)) or ((3301 -(830 + 64))>(6187 -(274 + 240 + 852)))) then v97=v89[v83];v98=v97[1 + 0 ];v114=1 + 0 ;end end break;end end end if ((v104==(1401 -(888 + 512))) or ((11883 -(22833 -14595))<(3058 -((3054 -(319 + 1336)) + (1314 -(697 + 245)))))) then if (((5860 -(2977 -(256 + 258)))>(44 + 50)) and (v98<=10)) then if ((v98<=(7 -3)) or ((8471 -5237)<=((5908 -4442) + 1495))) then if ((v98<=((3917 -2674) -(451 + 791))) or ((420 + 476)>((2700 -(9 + 186)) -(431 + 228)))) then if ((v98==(885 -((1492 -(816 + 497)) + 706))) or ((2170 -(435 + 602))<(95 + 293))) then local v133=0 + 0 ;local v134;local v135;while true do if (((1013 + 1259)<=(5692 -(628 + (473 -313)))) and (v133==(1 + 0))) then for v189=v134 + 1 ,v97[1067 -(476 + 587) ] do v135=v135   .. v95[v189] ;end v95[v97[1 + 1 ]]=v135;break;end if ((((2375 + 1720) -(713 + 208))>=(1642 -637)) and (v133==(0 -(0 + 0)))) then local v183=0 + 0 ;while true do if ((v183==(1 + 0)) or ((1395 + 1029)<=(2886 -(297 + 544)))) then v133=(377 + 1538) -(1806 + 108) ;break;end if ((v183==0) or ((10192 -(5773 -(92 + 14)))<=(3633 + 41))) then v134=v97[11 -8 ];v135=v95[v134];v183=(3 + 0) -2 ;end end end end else local v136=0 + 0 ;local v137;local v138;while true do if ((v136==(0 -0)) or ((5086 -(98 + 243))<(3515 -(918 + 327)))) then local v184=(3915 -2280) -(333 + 1302) ;while true do if ((v184==(2 -1)) or ((19181 -14437)<(6455 -3070))) then v136=4 -3 ;break;end if ((v184==((1242 -216) -(711 + 315))) or ((2800 -(245 + 861))>(3764 + 806))) then v137=1942 -(1705 + 237) ;v138=nil;v184=1 -0 ;end end end if ((v136==(1978 -(136 + 1841))) or ((2138 -(445 + 466))>=(4611 -(940 + 176)))) then while true do if ((v137==(927 -(215 + 712))) or ((8864 -5705)<(2347 -1126))) then v138=v97[345 -(153 + 190) ];v95[v138]=v95[v138]();break;end end break;end end end elseif (((265 -194)<=((4138 -(977 + 151)) + 1759)) and (v98<=(4 -2))) then v83=v97[171 -(69 + 99) ];elseif (((22707 -17961)>(2058 + 286)) and (v98==(219 -(46 + 170)))) then if (((333 + 2523)<(6084 -(30 + 661 + 1020))) and (v97[2 + 0 ]==v95[v97[3 + (926 -(826 + 99)) ]])) then v83=v83 + 1 + 0 ;else v83=v97[7 -4 ];end else local v157=0 -0 ;local v158;local v159;while true do if (((4828 -(1298 + 317))<(6632 -(216 + 922 + 520))) and (v157==(1 + 0))) then while true do if ((v158==(0 -(0 + 0))) or ((5389 -(718 + 17))<=(4969 -(38 + 1259)))) then v159=v97[2 + 0 ];v95[v159](v13(v95,v159 + 1 + 0 ,v97[5 -2 ]));break;end end break;end if ((((705 -(91 + 27)) -(262 + 325))==v157) or ((2855 -(188 + 75))<(81 + (432 -272)))) then v158=1276 -(622 + 654) ;v159=nil;v157=1 + 0 ;end end end elseif ((v98<=(4 + 3)) or ((9981 -5556)<=(247 + 1222))) then if (((8162 -4384)>=(901 -(227 + 322))) and (v98<=(74 -(5 + 64)))) then v65[v97[4 -1 ]]=v95[v97[2 + 0 ]];elseif (((4823 -3055)<(5894 -2996)) and (v98>(12 -6))) then local v160=0 -0 ;local v161;local v162;local v163;local v164;while true do if (((175 + 330)>=(428 -185)) and (v160==(1922 -(254 + 1667)))) then v163=nil;v164=nil;v160=1928 -(1314 + 612) ;end if (((3265 -(254 + 25))>=(317 + 180)) and ((1 + 1)==v160)) then while true do if (((3915 -1886)<=(3643 -(381 + 807))) and (v161==(0 + 0))) then local v206=(502 -(95 + 407)) + 0 ;while true do if ((v206==(0 -0)) or ((4252 + 376)==((1595 + 1150) -(76 + 54)))) then v162=0 -0 ;v163=nil;v206=1 -0 ;end if ((v206==(1413 -((2605 -1627) + 434))) or ((4555 -(1517 + 335))==((36212 -19178) -12862))) then v161=1784 -(175 + 1608) ;break;end end end if (((711 + 306 + 796)>(386 + (2874 -1820))) and (v161==(1266 -(1238 + 27)))) then v164=nil;while true do if ((v162==(0 + 0 + 0)) or ((3130 -(588 + 236))>(2468 + 1698))) then local v215=0 -0 ;local v216;while true do if (((807 -(119 + 203))<(16452 -12133)) and (((0 -0) -0)==v215)) then v216=0 -0 ;while true do if (((213 + 455)==(1128 -460)) and ((3 -2)==v216)) then v162=1174 -(121 + 1052) ;break;end if ((((14312 -3496) -7559)>(666 + 31 + 995)) and (v216==(284 -(70 + 214)))) then local v231=0 + 0 ;while true do if ((v231==(1406 -(958 + 448))) or ((9 + 1800 + 2099)>(2086 + 1994))) then v163=v97[2 + 0 ];v164=v95[v97[1681 -(292 + 1386) ]];v231=1;end if (((7116 -4976)>(60 + 82 + 100)) and (v231==(2 -1))) then v216=1264 -(651 + 612) ;break;end end end end break;end end end if ((v162==(2 -1)) or ((5914 -((939 -620) + 615))==(5439 -(379 + (1716 -(496 + 563)))))) then v95[v163 + (1638 -(77 + 1560)) ]=v164;v95[v163]=v164[v97[1 + 3 ]];break;end end break;end end break;end if ((v160==(0 + 0)) or ((2129 -(846 + 716))==(893 -(584 + (880 -664))))) then v161=0 + 0 ;v162=nil;v160=1 + 0 ;end end else v95[v97[1876 -(370 + 1504) ]]=v65[v97[1120 -(1004 + 113) ]];end elseif ((v98<=((8926 -7079) -(1678 + 161))) or ((596 + 8 + 31)>(1166 + 813))) then v95[v97[5 -3 ]]=v95[v97[(1875 -(284 + 127)) -(1318 + 143) ]];elseif (((1306 + 255)<((7653 -(575 + 1378)) -(42 + 1674))) and (v98==(1379 -(988 + 382)))) then if ((v95[v97[3 -(1 + 0) ]]==v97[8 -(8 -4) ]) or ((8579 -3997)<=(3897 -(626 + (1225 -(923 + 201)))))) then v83=v83 + (2 -1) ;else v83=v97[(446 -(132 + 312)) + 1 ];end else local v167=0;local v168;local v169;local v170;local v171;while true do if ((v167==(1 + 0)) or ((273 + 3282)==((3989 + 9353) -8596))) then local v195=0 + 0 ;while true do if ((v195==(2 -1)) or ((5678 -(1241 + 459))<=(1522 + 959))) then v167=85 -(29 + 54) ;break;end if ((1488==(216 + 1272)) and (v195==(0 + 0))) then v84=(v170 + v168) -(4 -3) ;v171=0 + 0 ;v195=1 -0 ;end end end if (((12684 -9832)>(3467 -(66 + 1410))) and (v167==(486 -(372 + 114)))) then v168=v97[1 + 1 ];v169,v170=v92(v95[v168](v13(v95,v168 + ((1838 -(299 + 98)) -(152 + 1288)) ,v97[3 + 0 ])));v167=3 -2 ;end if ((v167==(5 -3)) or ((642 + 2190 + 996)==(3286 -(627 + 1070)))) then for v201=v168,v84 do local v202=0 -(0 + 0) ;local v203;local v204;while true do if (((3598 -(137 + 7))<=(5058 -(7 + 119))) and (v202==(1 + 0))) then while true do if ((v203==(0 + 0)) or ((348 + 631 + 2432)>(4771 -(433 + 25)))) then v204=0 -0 ;while true do if ((v204==(816 -(88 + 728))) or ((5464 -1797)==(2631 + 915))) then v171=v171 + ((1 + 1) -1) ;v95[v201]=v169[v171];break;end end break;end end break;end if (((293 + 4422)==(2623 + 2092)) and (v202==((0 -0) -0))) then v203=(0 -0) -(1659 -(189 + 1470)) ;v204=nil;v202=1 + 0 ;end end end break;end end end elseif ((v98<=(1 + 1 + 13)) or ((2867 -1315)<=(1599 -(138 + 61)))) then if ((v98<=(1752 -(216 + 1524))) or ((1803 -(16 + 1154))==(392 + 466))) then if (((2195 -721)>=(321 + 554)) and (v98>(3 + 8))) then local v144=0 -0 ;local v145;while true do if ((v144==(0 + 0)) or ((273 + 73 + 1355)<=(3777 -(4035 -(1278 + 385))))) then v145=v97[1794 -(1737 + 55) ];v95[v145]=v95[v145](v13(v95,v145 + (1 -0) ,v84));break;end end else v95[v97[1182 -(608 + 572) ]]=v29(v90[v97[(2 -1) + 2 ]],nil,v65);end elseif (((282 + 767)<(2597 -(1127 + 65))) and (v98<=(22 -(8 + 1)))) then v95[v97[2 + (1695 -(1493 + 202)) ]]={};elseif ((v98>(7 + 7)) or ((5468 -(33 + 1304))<=(3017 -(1121 + 336)))) then v95[v97[1 + 1 ]][v97[1 + 2 ]]=v97[772 -(529 + 239) ];else v95[v97[1926 -(1573 + 351) ]]=v95[v97[6 -3 ]][v97[3 + 1 ]];end elseif ((v98<=(326 -(277 + 31))) or ((10195 -5616)<((2727 -(1048 + 44)) -(1390 + 94)))) then if ((v98<=(140 -(42 + (955 -(20 + 853))))) or ((813 + 3712)<=(8667 -5709))) then v95[v97[1 + 1 ]]=v97[10 -7 ];elseif ((v98==(34 -17)) or ((789 + 46)>(2792 + 1139))) then local v176=1208 -(979 + 229) ;local v177;local v178;local v179;while true do if ((((2638 + 1805) -(54 + 585))>=(175 + 1331 + 704)) and (v176==(82 -(35 + 47)))) then v177=(0 -0) -0 ;v178=nil;v176=1 -0 ;end if ((v176==(1 + 0)) or ((5516 -(1017 + 28))<((6625 -3986) -(521 + 227)))) then v179=nil;while true do if ((v177==(2 -1)) or ((1477 -(753 + (1978 -(1534 + 420))))<=(222 + 71))) then while true do if (((2329 -(491 + 257))>=(1677 -((1331 -(829 + 276)) + 523))) and (v178==(101 -(73 + 28)))) then v179=v97[1 + 1 ];v95[v179]=v95[v179](v95[v179 + (1845 -(325 + 1519)) ]);break;end end break;end if ((v177==(0 -0)) or ((4682 -3107)>(633 + 3519))) then local v207=(1296 -(1005 + 291)) + (0 -0) ;while true do if ((v207==(0 -0)) or ((40 + 4192)==(637 -(425 + (156 -74))))) then v178=0 -0 ;v179=nil;v207=1868 -(655 + 1212) ;end if (((10032 -6397)>=(36 + 3)) and ((3 -2)==v207)) then v177=1 -0 ;break;end end end end break;end end else v95[v97[5 -(1641 -(1161 + 477)) ]]();end elseif ((1540<(7340 -4049)) and (v98<=(604 -(563 + 22)))) then do return;end elseif ((v98>(1 + 19)) or ((5928 -4474)==(8110 -3845))) then v95[v97[5 -3 ]][v97[8 -5 ]]=v95[v97[(1161 + 454) -(1332 + 279) ]];else for v187=v97[7 -5 ],v97[3 -0 ] do v95[v187]=nil;end end v83=v83 + 1 + 0 ;break;end end break;end end end end A,B=v27(v11(v87));if  not A[1] then local v105=v63[4][v83] or "?" ;error("Script error at ["   .. v105   .. "]:"   .. A[2] );else return v13(A,2,B);end end;end if (v66==0) then v67=v63[1];v68=v63[2];v66=1;end end end return v29(v28(),{},v17)(...);end v15("LOL!163O00028O00026O00F03F030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403213O00682O7470733A2O2F706173746562696E2E636F6D2F7261772F727574754C674E7A03063O00736372697074027O004003063O004E6F7469667903103O00536372697074204C6F61642054616B6503053O0062656E63682O033O00206D73032B3O00682O74703A2O2F3O772E726F626C6F782E636F6D2F612O7365742F3F69643D312O30383034323933313503083O004475726174696F6E026O00244003043O004D61696E03083O00526F756E64696E672O0103073O0067657467656E7603063O004972697341640100033A3O00682O7470733A2O2F6170692E69726973612O702E63612F536372697074732F4972697342652O7465724E6F74696669636174696F6E732E6C7561002F3O0012103O00014O0014000100013O0026093O000E000100020004023O000E0001001206000200033O001206000300043O002007000300030005001210000500064O000A000300054O000C00023O00022O001200020001000100020B00025O001205000200073O0012103O00083O0026093O001F000100080004023O001F000100200E0002000100090012100003000A3O0012060004000B3O001206000500074O00110004000200020012100005000C6O0004000400050012100005000D4O000D00063O000200300F0006000E000F2O000D00073O000100300F0007001100120010150006001000072O00040002000600010004023O002E0001000E030001000200013O0004023O00020001001206000200134O000100020001000200300F000200140015001206000200033O001206000300043O002007000300030005001210000500164O000A000300054O000C00023O00022O00010002000100022O0008000100023O0012103O00023O0004023O000200012O00133O00013O00013O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403413O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F303373416C742F4D696D69632F6D61696E2F4E6F536B69644C6F6C2E6C756100083O0012063O00013O001206000100023O002007000100010003001210000300044O000A000100034O000C5O00022O00123O000100012O00133O00017O00083O00083O00083O00083O00083O00083O00083O00083O00093O002F3O00023O00033O00053O00053O00063O00063O00063O00063O00063O00063O00063O00093O00073O000A3O000C3O000C3O000D3O000D3O000D3O000D3O000D3O000D3O000D3O000D3O000D3O000D3O000D3O000D3O000D3O000D3O000E3O00103O00103O00113O00113O00113O00123O00123O00123O00123O00123O00123O00123O00123O00133O00143O00163O00",v9(),...);end
