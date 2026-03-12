# SAMP APK Patcher - Frida Gadget

Target: com.sampmobilerp.game (armeabi-v7a)
Inject point: com/sampmobilerp/launcher/MainActivity.smali

## Cara pakai
1. Ganti `input/target.apk` dengan APK terbaru
2. Edit `config/mode.txt` → `listen` atau `script`
3. Push → tunggu Actions → download `samp-frida-patched`

## Connect ke gadget (listen mode)
frida -H <IP_HP>:27042 -F
