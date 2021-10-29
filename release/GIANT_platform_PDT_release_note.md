### Aboud GIANT Platform

This is GIANT platform PDT historical release note

Admin platform

> It is used by INC and GSC administrators to manage e-Part firmware, FAQ, stores, dealer accounts... etc. Warning: Do not use for non-GIANT Group managers.

Service platform

> For Dealer use, Dealer can use service tools: Quick check, Get bike information, Bike setting, Diagnostic, Get history report... etc.

Connect tool

> Dongle application. Service tools must use this application to give instructions or control to e-Bike.



### 20211004 [GIANT platform]==~New==
####  2.6.2 [Admin platform]

> New add

- FAQ Management user guide
-  Allow mailboxes to have a plus string sign

> Fixed bug

- Role: ESC user, when use FAQ management pop up Error: Network Error
- FAQ Management website Product type and name missing filter
- After editing FAQ, other languages have a chance to disappear
- After deleting FAQ, other languages have a chance to disappear
- Can't return to the previous page correctly

#### 2.6.4 [Service platform] 

> Fixed bug

- FAQ cannot use the anchor link

#### 2.6.32 [Connect tool] 

NA

------

### 20210906 [GIANT platform]

####  2.6.0 [Admin platform]

>  New add

- DIA report Read start date 6/1 
- DIA report Remove download detail report 
- FAQ management (UI/UX hyper link+edit+multi language+preview)
**Fixed bug**
- UAT create account mail content and web link fix
- Undefined API
- DIA report qty error
- Download report will cause twice download
- Query E7FE11000 not found
- DIA report data SG[24] SmartGateway: 0
- AP Diagnostic history can't search  follow FN from 6/1~6/10
- Create dealer store"

#### 2.6.3 [Service platform] 

>  New add

- Diagnostic PDF multi language (use Diagnostic result language)
- BBSS angle test (for sorting not smooth BBSS detect)
- GENERAL BIKE INFO add System Wheel Circumference
- Name align website version should be = Service Platform version
- Oops message UI 
- CT manual active by short cut double click
- Dealer login with space
- FAQ update to 5 items
- Shimano add SyncDrive communication test
- DU18 compatible
- CAN controller rescue update

> Fixed bug

- Server error 3588 
- CT loop bug
- Error: Request failed with status code 500
- Can't find dongle
- JPN DU no auto
- Remote on/off update skip
- Bike information no information 
- On/Off button diagnostic picture and text
- DU9 diagnostic text

#### 2.6.32 [Connect tool] 

NA

------

### 20210531 [GIANT platform]

####  2.4.30 [Admin platform]

NA

#### 2.4.30 [Service platform] 

>  New add

- Shimano system compatible
- On/off compatible
- SyncDrive pro 2 compatible
- BBSS advance diagnostic (add Angel test in SyncDrive with BBSS)
- Diagnostic logic and format (Integrate BBSS test into SyncDrive)
- Diagnostic Report format Improvement (Clear and event code shown)
- Scan UI (Change USB driver reminder from Red to black)
- Update improve (Add Device name and current/target version)
- New EVO update improvement and multi language feature
(Firmware will update to 20210229 and then 20210330, if dealer stay in 20210229 bike will stay in Service Mode, please connect back to finish 20210330)
- QC logic improvement
- Solution Presentation architecture improvement (Solution stay even if the battery is removed)
- ODO issue fix (By use Motor ODO via firmware update), Platform remove ODO setting in bike setting and use Motor ODO as all the ODO in platform.
  ODO free Firmware version
  - SG10Y 20210524
  - Charge S5 20210514
  - ONE BLE/ANT+ 20210520
  - EVO S5 20210519
- CAN controller rescue update (For BBSS advance diagnostic) 
CAN controller Firmware need to update to 20201219 
BBSS Firmware need to update to 20201216
- Report UI improvement (GJ account remove momentum logo)
- QC result UI improvement  (Remove FW status and change icon)
- Bike Setting UI (Service Interval Maximum input remind)

> Fixed bug

- RC EVO missing data will fix with firmware version at 7/B"

#### 2.5.32 [Connect tool] 

NA