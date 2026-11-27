# M490J · Input Pre Amps

Ward-Beck Systems M490J, 1983|16. Wiki page: [M490J on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M490J.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 24 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 14 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 198 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 7 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 34 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1983 - M490J - P002 - 1-1.jpg](MANUALS/1983%20-%20M490J%20-%20P002%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivity** |  |
| &nbsp;&nbsp;Frequency response | bcc Lfc Noise: |
| **Harmonic distortion** |  |
| &nbsp;&nbsp;Source impedance | 150 ohms, balanced/unbalanced. |
| **Input impedance** | 750 ohms minimum |
| **Output impedances** | 000 ohms, balanced (program circuits) _ 60,000 ohms_ balanced (cue circuits) OOO ohms balanced (post direct) |
| **Output level** | dBm nominal _ +24 dBm maximum (equ va ent voltage 600 ohms / |
| **Phasing** | Input and output terminals designated by numbers are phase lower number numbered pair phase with lower number other numbered pair. |
| **Input levels** | (to operate CH ON, CH OFF Logic Logic 713 volts +16 +24 volts. |
| **External control output** | (Open collector current sink) |

## Circuit description

From [1983 - M490J - Mic Input Module (2).pdf](MANUALS/1983%20-%20M490J%20-%20Mic%20Input%20Module%20(2).pdf) pages 4-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

T h.. M490J pro&quot;i d e s com pl e l.. mic r o p hon.. chan n.. 1 fa c i l ili.. s, incl u siv.. of asl i d.. mixing a ll..nu alor, sec ec e s.. t ecrc rand mixing bus assign m.. nl switch e s, as r.. qu i red tor a m i.dng c onsol.. input.

I n p u land P.... a m pl i fie r

T h.. mU l u ally inter lock.. d INPUT SELECTORs witches SWI and S'tI 2 &lt;lll o w I h.. selection 0 1 one o f I wo &quot;&quot;.. ila bl.. mic...o pho n.. s o u &quot;'c.. s. Ana d d i t ion.. 1 con l.. cl iss u p plied 10'&quot; control purposes on each sw ilc h.

T h.. imp e d.. n c e pr.. sen l.. d b y t h.. i n p u l t r.. n s former T t iss ubs t.. nl ia l l y higher t h.. nth.. nominal source impedance 01 150 ohms. The s..cond_.. ry of T1 i s connect e d to I h e pr eam p lif i er cons i sling 0 1 01 through 07 and Zl. Inputs en sit i v i l Y oft h.. module maybe ve r-t.. d by a dju slment oft h.. SENSITIVITY control R25, co&quot;..ring II range of 30 d B. The b alan c ed pr.... mpl i f i er OU l put e pp ee r s e I modu l.. conn eclor P2, pin s6/F.

Twos..ri.. s conn.. c t.. d, b a l.. n c.. dins..r l points ar.. m.. de &quot;&quot;ai lab lea l P2, pins 6 /':, 9/), 5/ E and 7/H. opera ting a t.. nom i n.. 1 1.. &quot;.. 1 of 5 dBm. T h.. y allow I h.. ins.. r lion o fan ci l l a r y proc.. s singe Quip m.. n tin l O I h e mixing channels i g nal p a lh such as a compress o r. equ.. liz e... o r filter. The provision o f twos.....le s connector insert points p.. rm i l S the u t i l i z.. tion 0 1 lhe module ins t eeo systems such as I h e WB S mod.. 1 R I2OD /R2ODO c O&lt;&quot;&gt;so l.. s • Int hes n d similar app l i cations, I h.. lun cti on s associ a t.. d with Ihe 1.. lt.. n d right Ins.. rl ion S.. lec l o rs (M 499) m.. y both b e inserted into the channel, with t h.. left chan n e 1 ins e r l l unction preceding the right channel function.

From I h ein se r t points, the signal i s rout.. d 10 ATT I, a ba l an c..d

slide allen u.. l o... fea luring os continuous mixing r.. nge 0 1 mo l''' I han

70 d B p...io r to c Ul o lI. The CUE channel feed i s l a k.. n I rom the input

side o f the all..n u at or.

Prow ' a m Channel Switch.

2 2 is a CMOS analogs witCh, s ervin gas thea c t ives witching element of the PROGRAM channel. The control voltage to operate 2 2 is derived from the logic circuitry within the module and is coupled to 21 via CR l. to switch the Channel ON, this cont roi voltage i sin the order of 10 volts. When the control voltage drops to 0 volts, the switch will be OFF, result ing ina signal attenuation o f more than 100 d B.

Following 22, int e grated cirx: ui t S 2 3 and 2 4 amplify the audios ig n alto a nominal level of 0 dBm (equ iva lent volta g e). From thea mpli fie r output, the signal is routed tot heP ROGRAM ASSIGNs witches SW4 and SWS via PANs witch SW3 and PAN Control R6S to R68.

Program Outputs

Both PROGRAM outputs PI and P2 are designed t o feed into stereo buses and each i s divided into ale ft and aright outPut. Operation o f ASSIGNMENT SWlTCHE S SW4 o r SWS wi il result ins im u l tan eo u s assignment to both left and right channels of thea p prop r i ate mi &gt;&lt;ing buses. With thea id o f the PAN contrOl, the signal d istr ib u t ion between the left and right output buses can b e continuously adjusted.

The CUE signal originates from abridging take o lf a t the input of the slide a lten ua tor. Owing to the high input imp e dance of the CUE channel, its operation has noe ff ec ton the main PROGRAM Channel. 25 r e pr n e n t s thea u d ios witch forth e CUE channel. Similarly [0 22, the control voltage for 2S is generated int h e logic circuit r y a s described further on. The output o f 25 is followed b y the booster amplifier 26, which int urn feeds the Cue bus mixing network At Ol through R IOlo.

Post Direct Output p s.

The outPut of booster amp li fie r 23-24 i stake n before the PANs witCh

and routed tot heP OST DIRECT output a t PI _20,21. The output level

is dBm (volt age r e: 600 ohms) under nominal conditions.

**CIRCUIT OESCRIP TIO N**

FOldback OU l Puts

The FOLDBACK oUlpul S, like the POST O IRECT OU l put, are lake n from the booster amplifier output &quot; i a level cOntrols RI SO-RIS ! l FBI) and RI S2_R15J l F B2). FBI and F B 2 appear a l ccoo ecto rPI _I I, 12 and PI-13,14re sp ect ive l y.

The control vOltages required to operate the PROGRAMs witch l2 and the CUEs witch Z 5 a r&quot;, generated with [ he aid o flog i c circuit r y utiliZing integrated c i n: u i l S Z 7 through ZIO.

Z8 i s CMOS dual f lip_f lop se r &quot; ing as ala tc h 10 maintain the s ttl t u s of Z2 and Z5, once they ha&quot;e been set toe i l her the ON or the OFF position.

A number of i n di&quot;idu a l inp u l functions g o &quot; er n the slat u s of med U1I1 flip _fl o p Z8. A description o f each input function follOws:

When power i sin i tia l l yap plied 10 lhe system, the combination of CR9, CRIO. CR II and C40 will pull down both &quot;c lear &quot; inputs of Z8 un ti i C40 i s fully charged. l hus ensuring that switChes Z 2 and Z5 are int h e OFF po s i lion.

Momentary operation of the CHANNEL ON s w i l c h SWg will produce a neg llli &quot;e going pulse a t Z8, pin 2 and &quot;c eserthe Asec tion o f Z8. AItern ali &quot; ely, a momentary ground closure o f the EXTERNAL CHANNEL ON con l r olin put III P2, pin N will result i n lh e same condition.

Once l h e flief lop i s &quot;pre sel&quot;, its o ulput i spin 15 changes f m m 0 to I (lI.pproximll. tely 10 va ll s).

This will CauSe lhe PROGRAMs witCh Z2 10 switch ON. Fur ther

more, 012 will saturate resulting int h e CHANNEL ON ind i calo r

lamp DSJ to sw i lC hon. With 01 2 Sal u rated, the &quot;coot rotc o mmo n &quot; POl enti ala p p ell. rs a t thee millers of OIJ and 014.

**M4 90J MIC INPUT MOOULE**

Apo sili ve base pO len li,, 1 i sap plied to either 01 3 &quot; n d 0 14, depending on wh e l her INPUT SELECTORs w i lCh SWI o r SW2 is depressed. Effectively, Q13 &quot; n d Q14 operates im i !&quot; r ly 10 two AND gates. The collectors o f Ih e Iwo Ir&quot;n sis tors represent the outputs oft h e AND gates.

They &quot; p pear atP 2, pin 13 and P. These le r mina ls are capable of sink ing &quot; maximum current of 40 mAe ach from a 24 volt source &quot;nd maybe used for muting purpos.....

When operating Ih e CHANNEL ON switch SW9, a separate con l&quot;c I i.. cl o s.. d, ace.. ss lb le &quot; t P2, pins 15/S. This cont ec t maybe used lor con lrol o r signaling purposes.

Pin R of P2 isis ola ted through diod.. CR 3. When conn.. ct.. din parallel with the Same o u lp u t of other modul.. s, i l prov id.. s &quot; convenient OR g &quot; te co nf i g u r&quot; tion, suitable to r-e set a Common timer each time a CHANNEL ON button is depressed.

Mom e n l a r y operation oft h e CHANNEL OFFs wi lc h SW8 o r mom enl &quot;ry ground closure of the EXTERNAL CHANNEL OFF control input e t P2, pin 12 will result in 5 n e ga nve going pulse a t ZS, pin 3 and &quot;cl e a r&quot; theA ~ 'Sec lion o f ZS, producing 01.'01 15 &quot; t Z8, pin 15. Consequ e n lly, Z2 wills witch OFF, 0 12 will SlOP con d UCl ing, causing OS3 10 e Xll n g u ish, and the muting con lrol outputs atP 2, pins 13 and P will b e dis &quot;b led.

A sep ara te cont act is a v &quot; ila b leon SWS and Is access ib le at P2, pins 17/ U.

A separate CHANNEL OFF 1&quot;ll y lamp is bu ill i n lo SWS &quot;nd i s connected to P2, pins IS / V.

The B~ sec lion of ZS Is used to control Ih e solids l&quot; le cue

s wi l c h 2 5. The flip _f lop will changes tate each time a

negative going trans i l lon take 'S place a l pin 6 o f Z8. Con se

qu enll y, with each i n PU I pulse, the CUE ch&quot;nnel willa l te rna te between ON &quot; nd OFF.

**CIRCUIT OESCR IPT ION**

This change of state can be brought about by any Ihree different methods:

a l Momentary operation of the CUEs witCh SW12 (C). b) Momentary ground closure o f the EXTERNAL CUE input a t 1'2, pin 11.

c ] Operation o f the &quot;o....e r pres.. &quot; switch SWl l, tce e tees l idea tt e n u a tor beyond the &quot; i nf i nIt e&quot; po s i lion.

The ON status o f the CUE chan n e i is indicated b y DS2. w n ic his d r i....en b y Cll.

Ana d d i tional fea lure enSureS that the CUE c h&quot; nn e l willa lwa ys switCh to OFF when e....e r the slide a ttenu a tor Is mo....e dOn to or aWIlY from the &quot; Infinite &quot; position, regardless of its priors tate. The control signal for Ih is action i sin i tia ted b y the change o f state o f the ATTENUATOR CUTs witch SW10. The result ant le....e l change, being either po siti....e or n egaliv e going, isp ro ce sse d through 27, Z9 and 210. The output produced atp i n 4 o r 210 willa l ways bean e ga tive going pulse of app ro &quot;i ma tely 500 mIl li seconds duration. CR ll passes this pulse to Z8, pin 8, thereby &quot; clear in g&quot; Ih e B_Se&lt;:tion of the f lI pfl op, andre Sult ing in pin 11 o f Z8 to.. witch to l or remain a t) 0 volts. in l urns witch ing the CUEs witch 25 to OFF.

All logic control inputs are buffered 10 guard again s tsp u rio us noise and switch bounce.

Power Supply Decoupling

Powers u p ply de&lt;:o u p l ing isp ro....i d e d b y R146 to R149 and C50 10 C53. CR16 and CR17 serve top reven tamp l i fie r damage int he event of supply voltage re....e e set • The d e&lt;:oupl lng n etwor~ drops Ih e +/ -25 volts u p ply rails to a nom ina l voltage o f +/ _t 8 v o ln. C1 5

de&lt;:oup les and filters the positives u p ply rail, resulting ina n

output of +t 2 volts to op erale the CMOS circuit r y. Ina ddi ton,

and 24 are further d e&lt;:oupl ed b y RS4, RS5, C21 and C22.

**PARTS LIST**

M490J MfC iNPUT MODULE

**MFG PART NUMBER**

Allen u ato r, oj. connector 1550 /A H35/ 100

cr delete 0 Capacitor sec Philips 222 2_6 30 _03 561

u F/25 u F/25

22 22-6 36 -7 047 9

**T3 9OC475 M02 5AS**

C6 2.2p F Philips 22 22_6 36_03 226 cr J. 9p F 222 2_6 36 _09 396

&quot; 0 uF / 6V 10 u F /25, Kernel TJ90E157M006A S TJ 9OCl 06 M0 25AS etc 220 uFl l0V TJ 90 F 2 27M0 10AS

CO, 150pF Philips 2222 -636-70151 cia 4.7pF 2222_636_09476 CD 220 u F/l0 v Kernet TJ90F227M010AS cu 4.7 u F/l0 V TJ908475MOlllAS CO&gt; 4.7 uF/ l 0 V

ere 0.33 uF /35 V T J90AJJ4MOJ5A S ct r to u F/ 2S v T39OC106M025AS erato u F/ 2S v COO 4.7 p F P h:, lips

**00 U**

u F/ 2 S v

uF /25 V uF/1 0 V CZ' 33uF/1 0 V c zs 6600 pF

COO 2.2 u F/ 25 V T3908225M025A S C27 U u F/ l 0 V TJ90B 47 5M010 A5 C26 U u F/ l 0V C20 a.a uF/16 V

e. a u F/16 V

U uF/1 0V C J2 U uF /l0 V

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2VhTnhwV3dPd3M/view?resourcekey=0-cose9mWlImCddfnPQJIqvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2VhTnhwV3dPd3M&resourcekey=0-cose9mWlImCddfnPQJIqvg" width="240" alt="1983 - M490J - 490-04-020 - EAEN DEPREATED ENABIET PAM NINOL RISO-RISI CONTROLE IEVA.jpg"></a><br><sub>1983|16 · 490-04-020 - EAEN DEPREATED ENABIET PAM NINOL RISO-RISI CONTROLE IEVA · <a href="MECHANICAL/1983%20-%20M490J%20-%20490-04-020%20-%20EAEN%20DEPREATED%20ENABIET%20PAM%20NINOL%20RISO-RISI%20CONTROLE%20IEVA%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWdFS0MtT0tlZmc/view?resourcekey=0-5ghoWvsxmHytVXbBmeZn7Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWdFS0MtT0tlZmc&resourcekey=0-5ghoWvsxmHytVXbBmeZn7Q" width="240" alt="1983 - M490J - 490-04-020 - IIGNA DUCDOSE IROM REMOLE IOCATLON RELATED THE DARILCULAR.jpg"></a><br><sub>1983|16 · 490-04-020 - IIGNA DUCDOSE IROM REMOLE IOCATLON RELATED THE DARILCULAR · <a href="MECHANICAL/1983%20-%20M490J%20-%20490-04-020%20-%20IIGNA%20DUCDOSE%20IROM%20REMOLE%20IOCATLON%20RELATED%20THE%20DARILCULAR%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1mUEnW2UqLxXTamWjfaTOv9aPSDy6to8T/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1mUEnW2UqLxXTamWjfaTOv9aPSDy6to8T" width="240" alt="19xx - M490J - DOC - 490-03-035 - FREE FROM MARKS AND SCRATCHES.jpg"></a><br><sub>19xx - M490J - DOC - 490-03-035 - FREE FROM MARKS AND SCRATCHES</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1aME9HVnC1lwTkThIaRK-3XEx0YoXsGnJ/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1aME9HVnC1lwTkThIaRK-3XEx0YoXsGnJ" width="240" alt="19xx - M490J - DOC - 90-04-020 - JIANI INDLLCANE ANLUS NIS SWITCH AISO IURN CUE.jpg"></a><br><sub>19xx - M490J - DOC - 90-04-020 - JIANI INDLLCANE ANLUS NIS SWITCH AISO IURN CUE</sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M490J.stl`](MECHANICAL/M490J.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M490J)

- **Size:** 43.83 × 268.58 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 11 holes and cut-outs, 1 knobs (front panel: `MECHANICAL/M490J - front panel.svg`)
- the drawn panel is 0.11 wide to high, the size 0.16: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M490J.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR2RVeGRqb2Y1eG8/view?resourcekey=0-NJu1DOuOth4ScFUYiwvB2Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR2RVeGRqb2Y1eG8&resourcekey=0-NJu1DOuOth4ScFUYiwvB2Q" width="240" alt="1983 - M490J - 490-01-010 - ENG SCTTLAT MIC INPUT MODULE.jpg"></a><br><sub>1983|16 · 490-01-010 - ENG SCTTLAT MIC INPUT MODULE · <a href="SCHEMATICS/1983%20-%20M490J%20-%20490-01-010%20-%20ENG%20SCTTLAT%20MIC%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSDFtaGZUcHVxcUk/view?resourcekey=0-l-hFTDUkhdIRuyZb_x-XYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSDFtaGZUcHVxcUk&resourcekey=0-l-hFTDUkhdIRuyZb_x-XYA" width="240" alt="1983 - M490J - 490-01-010 - EXTERNAL CONTROLS OFF CUE CUE.jpg"></a><br><sub>1983|16 · 490-01-010 - EXTERNAL CONTROLS OFF CUE CUE · <a href="SCHEMATICS/1983%20-%20M490J%20-%20490-01-010%20-%20EXTERNAL%20CONTROLS%20OFF%20CUE%20CUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMW8xSmktYzZoWVU/view?resourcekey=0-Qja1W9B2zzOBEcr1FQVcmQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMW8xSmktYzZoWVU&resourcekey=0-Qja1W9B2zzOBEcr1FQVcmQ" width="240" alt="1983 - M490J - 490-02-012 - LAST COMPOHEUT CESIGUIT.jpg"></a><br><sub>1983|16 · 490-02-012 - LAST COMPOHEUT CESIGUIT · <a href="SCHEMATICS/1983%20-%20M490J%20-%20490-02-012%20-%20LAST%20COMPOHEUT%20CESIGUIT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNVR5aFNQeVdzb3c/view?resourcekey=0-RylVUTJMhNQy4mlFeLiyMw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNVR5aFNQeVdzb3c&resourcekey=0-RylVUTJMhNQy4mlFeLiyMw" width="240" alt="1983 - M490J - 490-02-012 - MIC INPUT MODULE.jpg"></a><br><sub>1983|16 · 490-02-012 - MIC INPUT MODULE · <a href="SCHEMATICS/1983%20-%20M490J%20-%20490-02-012%20-%20MIC%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX29KVU1YOF9lS0E/view?resourcekey=0-AzuFVMxFPkA39GJZpsReZQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX29KVU1YOF9lS0E&resourcekey=0-AzuFVMxFPkA39GJZpsReZQ" width="240" alt="1983 - M490J - 490-06-022 - CQMPONENI SDE EALOAN.jpg"></a><br><sub>1983|16 · 490-06-022 - CQMPONENI SDE EALOAN · <a href="SCHEMATICS/1983%20-%20M490J%20-%20490-06-022%20-%20CQMPONENI%20SDE%20EALOAN%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd1liNVlGSkRObVU/view?resourcekey=0-aAIMN-vmYa76RpWBEM5oAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd1liNVlGSkRObVU&resourcekey=0-aAIMN-vmYa76RpWBEM5oAw" width="240" alt="1983 - M490J - 490-06-022.jpg"></a><br><sub>1983|16 · 490-06-022 · <a href="SCHEMATICS/1983%20-%20M490J%20-%20490-06-022%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M490J - RTO-144 Connections.pdf`

## RTO-144 pinout

13 contacts (P1), 21 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | LEFT PGRM 1 | audio | A3 + | high |
| 1 | MIC IN A | in | A1 + | high |
| 2 | LEFT PGRM 1 | audio | A3 - | high |
| 3 | RIGHT PGRM 1 | audio | A4 + | high |
| 3 | MIC IN B | in | A2 + | high |
| 4 | RIGHT PGRM 1 | audio | A4 - | high |
| 5 |  | unread |  | low |
| 6 | INSERT SEND | out | B1 + | high |
| 7 | INSERT RETURN | in | B2 + | high |
| 13 |  | unread |  | low |
| 13 |  | unread |  | low |
| 15 | CTL | control |  | low |
| 17 |  | unread |  | low |
| 19 | -25 V | power |  | high |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| A | MIC IN A | in | A1 - | high |
| C | MIC IN B | in | A2 - | high |
| F | INSERT SEND | out | B1 - | high |
| H | INSERT RETURN | in | B2 - | high |
| L |  | unread |  | low |
| P |  | unread |  | low |
| V |  | unread |  | low |

**Straps:** Insert: JMP.6.7 · Insert: JMP.F.H

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZFRJTl9RbWI1Z1k/view?resourcekey=0-ptQtwqxl6FzYJXl2iAqIWQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZFRJTl9RbWI1Z1k&resourcekey=0-ptQtwqxl6FzYJXl2iAqIWQ" width="240" alt="1983 - M490J - Mic Input Module (2).pdf"></a><br><sub>1983|16 · Mic Input Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT3BQZXdfXzNIUEU/view?resourcekey=0-wbzq3gdVm-YZmWTlXP8tfQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT3BQZXdfXzNIUEU&resourcekey=0-wbzq3gdVm-YZmWTlXP8tfQ" width="240" alt="1983 - M490J - Mic Input Module.pdf"></a><br><sub>1983|16 · Mic Input Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUGRHYkZVOWhFY28/view?resourcekey=0-_iaHDozBmjKj66rPcrwV6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUGRHYkZVOWhFY28&resourcekey=0-_iaHDozBmjKj66rPcrwV6w" width="240" alt="1983 - M490J - P001 - Title Page.jpg"></a><br><sub>1983|16 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV2VZQTVoOVVCbVU/view?resourcekey=0-u9n5ETAOe2gKhZYDky3wkw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV2VZQTVoOVVCbVU&resourcekey=0-u9n5ETAOe2gKhZYDky3wkw" width="240" alt="1983 - M490J - P002 - 1-1.jpg"></a><br><sub>1983|16 · P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVFYSDZqdFg0Q1k/view?resourcekey=0-yMrS6NDCbB8pwMgMmvs5Qg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVFYSDZqdFg0Q1k&resourcekey=0-yMrS6NDCbB8pwMgMmvs5Qg" width="240" alt="1983 - M490J - P003 - 1-2.jpg"></a><br><sub>1983|16 · P003 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWEZvSTVWUXluRGs/view?resourcekey=0-8Kb1_qD0u4v3vWLpx0ZUwQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWEZvSTVWUXluRGs&resourcekey=0-8Kb1_qD0u4v3vWLpx0ZUwQ" width="240" alt="1983 - M490J - P004 - 2-1.jpg"></a><br><sub>1983|16 · P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeWVXYmRWRVlCYTg/view?resourcekey=0--3kg0DXdBanq-6Rnroaibg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeWVXYmRWRVlCYTg&resourcekey=0--3kg0DXdBanq-6Rnroaibg" width="240" alt="1983 - M490J - P005 - 2-2.jpg"></a><br><sub>1983|16 · P005 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZUNndTY5SXY3Sk0/view?resourcekey=0-ls-LiWn463kaR2rKwixnVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZUNndTY5SXY3Sk0&resourcekey=0-ls-LiWn463kaR2rKwixnVw" width="240" alt="1983 - M490J - P006 - 2-3.jpg"></a><br><sub>1983|16 · P006 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSF9iUVNtTW93NVE/view?resourcekey=0-rJZopHMh26GPL-hWE9nMzg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSF9iUVNtTW93NVE&resourcekey=0-rJZopHMh26GPL-hWE9nMzg" width="240" alt="1983 - M490J - P007 - 2-4.jpg"></a><br><sub>1983|16 · P007 - 2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcWNnSEV5NXQ0WDA/view?resourcekey=0-YBhnVZx9SPNok0Pw1lnSGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcWNnSEV5NXQ0WDA&resourcekey=0-YBhnVZx9SPNok0Pw1lnSGw" width="240" alt="1983 - M490J - P008 - 2-5.jpg"></a><br><sub>1983|16 · P008 - 2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUXpHY1ZSX1hrN2s/view?resourcekey=0-s_wKp-FVC__vcRD21N2svw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUXpHY1ZSX1hrN2s&resourcekey=0-s_wKp-FVC__vcRD21N2svw" width="240" alt="1983 - M490J - P009 - 3-1.jpg"></a><br><sub>1983|16 · P009 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclE1NHhoSmdnV0E/view?resourcekey=0-cwicZfs0v6Yqa1MIrf9JnA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclE1NHhoSmdnV0E&resourcekey=0-cwicZfs0v6Yqa1MIrf9JnA" width="240" alt="1983 - M490J - P010 - 3-2.jpg"></a><br><sub>1983|16 · P010 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNVpEUjB3b1VvYjg/view?resourcekey=0-YTDw8H4DmtIzBLEhSWsq6g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNVpEUjB3b1VvYjg&resourcekey=0-YTDw8H4DmtIzBLEhSWsq6g" width="240" alt="1983 - M490J - P011 - 3-3.jpg"></a><br><sub>1983|16 · P011 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbU1fTXNzTnkwckk/view?resourcekey=0-XqrJFdfbgHXUyUQA_5yUWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbU1fTXNzTnkwckk&resourcekey=0-XqrJFdfbgHXUyUQA_5yUWg" width="240" alt="1983 - M490J - P012 - 3-4.jpg"></a><br><sub>1983|16 · P012 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWWVPbWY1aHphcHM/view?resourcekey=0-M5UCK2XjQKqExOswQA0tAQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWWVPbWY1aHphcHM&resourcekey=0-M5UCK2XjQKqExOswQA0tAQ" width="240" alt="1983 - M490J - P013 - 3-5.jpg"></a><br><sub>1983|16 · P013 - 3-5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZGN1dExVc0gwMTQ/view?resourcekey=0-d4Xb7rzcJsYD-KAgjzmuUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZGN1dExVc0gwMTQ&resourcekey=0-d4Xb7rzcJsYD-KAgjzmuUw" width="240" alt="1983 - M490J - P014 - 3-6.jpg"></a><br><sub>1983|16 · P014 - 3-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZS1nTW54WC1Vb0E/view?resourcekey=0-Q1WF2QBJMFDzUjsLQGMOqw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZS1nTW54WC1Vb0E&resourcekey=0-Q1WF2QBJMFDzUjsLQGMOqw" width="240" alt="1983 - M490J - P015 - 3-7.jpg"></a><br><sub>1983|16 · P015 - 3-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS3NHdFoySjVYWjA/view?resourcekey=0-txB6HSNHRqItgiC3i0nLDA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS3NHdFoySjVYWjA&resourcekey=0-txB6HSNHRqItgiC3i0nLDA" width="240" alt="1983 - M490J - P016 - 3-8.jpg"></a><br><sub>1983|16 · P016 - 3-8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZlRsV2x5VFZOaGc/view?resourcekey=0-rvmZ5kumV1ER7bmHrJnMig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZlRsV2x5VFZOaGc&resourcekey=0-rvmZ5kumV1ER7bmHrJnMig" width="240" alt="1983 - M490J - P017 - 4-1.jpg"></a><br><sub>1983|16 · P017 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcEg3UjFxNEwwcVE/view?resourcekey=0-edYaWd3QQLo-cIjeLxwRbQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcEg3UjFxNEwwcVE&resourcekey=0-edYaWd3QQLo-cIjeLxwRbQ" width="240" alt="1983 - M490J - P018 - 4-2.jpg"></a><br><sub>1983|16 · P018 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd0F0WXkwYXk4REE/view?resourcekey=0-JVSYK4Y_JF2LhQvjxOAs5g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd0F0WXkwYXk4REE&resourcekey=0-JVSYK4Y_JF2LhQvjxOAs5g" width="240" alt="1983 - M490J - P019 - CD4016.jpg"></a><br><sub>1983|16 · P019 - CD4016</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc2xtemRnNGdWVFk/view?resourcekey=0-6_FAhExcbRSEW8ysscGMYQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc2xtemRnNGdWVFk&resourcekey=0-6_FAhExcbRSEW8ysscGMYQ" width="240" alt="1983 - M490J - P020 - 74C76.jpg"></a><br><sub>1983|16 · P020 - 74C76</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbi1aZTF1TUdOY0E/view?resourcekey=0-kRjVCzauA_CQ0FkoHkDfyA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbi1aZTF1TUdOY0E&resourcekey=0-kRjVCzauA_CQ0FkoHkDfyA" width="240" alt="1983 - M490J - P021 - 74C221.jpg"></a><br><sub>1983|16 · P021 - 74C221</sub></td></tr>
</table>

Not on Google Drive yet: `M490J - P020 - 74C76.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1983 - M490J - 490-01-010 - ENG SCTTLAT MIC INPUT MODULE.kicad_sch](KICAD/1983%20-%20M490J%20-%20490-01-010%20-%20ENG%20SCTTLAT%20MIC%20INPUT%20MODULE.kicad_sch)
- [1983 - M490J - 490-01-010 - EXTERNAL CONTROLS OFF CUE CUE.kicad_sch](KICAD/1983%20-%20M490J%20-%20490-01-010%20-%20EXTERNAL%20CONTROLS%20OFF%20CUE%20CUE.kicad_sch)
- [1983 - M490J - 490-02-012 - LAST COMPOHEUT CESIGUIT.kicad_sch](KICAD/1983%20-%20M490J%20-%20490-02-012%20-%20LAST%20COMPOHEUT%20CESIGUIT.kicad_sch)
- [1983 - M490J - 490-02-012 - MIC INPUT MODULE.kicad_sch](KICAD/1983%20-%20M490J%20-%20490-02-012%20-%20MIC%20INPUT%20MODULE.kicad_sch)
- [1983 - M490J - Mic Input Module (2) p25.kicad_sch](KICAD/1983%20-%20M490J%20-%20Mic%20Input%20Module%20(2)%20p25.kicad_sch)
- [1983 - M490J - Mic Input Module p25.kicad_sch](KICAD/1983%20-%20M490J%20-%20Mic%20Input%20Module%20p25.kicad_sch)
- [M490J.kicad_sym](KICAD/M490J.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
