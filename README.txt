PvP Bot (Fabric 1.21.11, client-side)

BUILD TANPA PC:
1. Buat repo GitHub baru, upload SELURUH isi folder ini (termasuk .github).
2. Tab "Actions" -> workflow "build" jalan otomatis (atau Run workflow).
3. Setelah hijau, buka run-nya -> Artifacts -> "pvpbot-jar" -> download, ekstrak,
   ambil file pvpbot-1.0.0.jar, taruh di folder mods Zalith (butuh Fabric API).

PAKAI (ketik di chat):
 /pvpbot gui         buka menu (tombol besar, cocok layar sentuh)
 /pvpbot crystal     toggle auto crystal (butuh end crystal + obsidian/bedrock di sekitar target)
 /pvpbot anchor      toggle auto anchor (butuh respawn anchor + glowstone di hotbar; hanya Overworld/End)
 /pvpbot off         matikan semua
 /pvpbot delay 2     jeda antar aksi (tick)
 /pvpbot mindamage 6 /pvpbot maxself 6 /pvpbot range 8

Item harus ada di HOTBAR. Target = pemain terdekat dalam range.
