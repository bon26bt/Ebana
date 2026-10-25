# EBANA — Android Build Starter

Kun faayila jalqabaa appii EBANA gara Android projecttti ijaaruuf qophaa'e dha.

## APK argachuuf (Samsung A17 irraa)
1. ZIP kana extract godhi.
2. GitHub keessatti repository haaraa uumi (fakkeenyaaf `ebana-reminder`).
3. Faayilota keessaa hundaa repository irratti upload godhi; `.github/workflows/android.yml` dabalatee.
4. Tab **Actions** bani; workflow **Build EBANA Android APK** filadhu.
5. **Run workflow** tuqi; build xumuramu eegi.
6. Workflow milkaa'e booda artifact **EBANA-debug-apk** buusi; ZIP artifact keessaa `app-debug.apk` baasi.
7. APK install gochuuf Android irraa hayyama “Install unknown apps” barbaachisuu danda'a.

## Waan beekuu qabdu
- Kun starter build pipeline dha; APK hin ijaaramin.
- Ijaarsa Android native keessatti alarm yeroo appiin duubatti/cufamee jiru sirnaan qindeessuu fi yaadachiisota scheduled local notification waliin walitti hidhuun hojii itti aanu dha. Web prototype keessaa timer/notification qofti alarm sirrii yeroo hunda hin mirkaneessu.
- Google Account backup ammas hin walitti hidhamne; JSON export/import qofatu prototype keessatti jira.
- Date picker HTML ammaa Gregorian dha. Kaalaandara Itoophiyaa guutuu fi date conversion verified gochuun dura, appii kana akka release xumurameetti hin fayyadamin.
- Workflow debug APK qofa ijaara; Play Store release signing hin qabu.
