# Swift iOS Agent Skills

Koleksi pribadi 15 skill Swift/iOS yang telah terpasang di Codex. Repo ini menyimpan snapshot agar koleksi dapat ditinjau, dicadangkan, dan dipasang kembali. Instruksi skill dan aset berasal dari penulis upstream; koleksi ini tidak mengklaim kepemilikan atas karya mereka.

## Daftar skill

| Skill | Kemampuan | Lisensi sumber |
| --- | --- | --- |
| [app-intents](skills/app-intents/SKILL.md) | Siri, Shortcuts, Spotlight, dan aksi aplikasi pada permukaan sistem. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [background-processing](skills/background-processing/SKILL.md) | BGTaskScheduler, pekerjaan latar belakang, dan background transfer. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [ios-networking](skills/ios-networking/SKILL.md) | URLSession, REST, WebSocket, pagination, retry, dan cache. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [ios-simulator](skills/ios-simulator/SKILL.md) | Pengelolaan dan pengujian iOS Simulator dengan simctl. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [push-notifications](skills/push-notifications/SKILL.md) | Notifikasi lokal/APNs, rich notification, dan notification extension. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [storekit](skills/storekit/SKILL.md) | Pembelian dalam aplikasi dan langganan dengan StoreKit 2. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [swift-codable](skills/swift-codable/SKILL.md) | Model JSON/property list, encoding, dan decoding. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [swift-concurrency](skills/swift-concurrency/SKILL.md) | Swift concurrency, actor, Sendable, dan keamanan data race. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [swift-security](skills/swift-security/SKILL.md) | Keychain, biometrik, CryptoKit, dan penyimpanan kredensial. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [swift-testing](skills/swift-testing/SKILL.md) | Swift Testing, pengujian async, dan migrasi XCTest. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [swiftdata](skills/swiftdata/SKILL.md) | Model, query, relasi, migrasi, dan sinkronisasi SwiftData. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [swiftui-expert-skill](skills/swiftui-expert-skill/SKILL.md) | SwiftUI iOS/macOS: state, komposisi view, layout, animasi, dan migrasi API. | [MIT](licenses/AvdLee--SwiftUI-Agent-Skill.txt) |
| [swiftui-pro](skills/swiftui-pro/SKILL.md) | Review SwiftUI: API modern, maintainability, dan performa. | [MIT](licenses/twostraws--SwiftUI-Agent-Skill.txt) |
| [swiftui-uikit-interop](skills/swiftui-uikit-interop/SKILL.md) | UIViewRepresentable, UIHostingController, dan integrasi UIKit–SwiftUI. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |
| [widgetkit](skills/widgetkit/SKILL.md) | Widget, timeline, interaksi, dan kontrol Control Center. | [PolyForm-Perimeter-1.0.0](licenses/dpearson2699--swift-ios-skills.txt) |

## Penggunaan di Codex

Minta Codex memasang koleksi ini dengan skill installer:

> Gunakan $skill-installer untuk memasang seluruh 15 skill dari https://github.com/Irc-7/swift-ios-agent-skills. Skill berada di skills/<nama-skill>. Lewati skill yang sudah terpasang.

Repo ini privat, sehingga akun atau kredensial GitHub yang digunakan saat memasang harus memiliki akses. Tidak ada kredensial yang disimpan di repo ini.

Setelah terpasang dan tersedia dalam daftar skill sesi, Codex memilih skill berdasarkan kecocokan permintaan dengan nama/deskripsinya. Untuk memilih secara eksplisit, sebutkan misalnya `$swift-concurrency`, `$swift-testing`, atau `$swiftui-expert-skill`. Kata “Swift” saja tidak menjamin semua skill digunakan.

Contoh:

- “Gunakan $swift-concurrency untuk memperbaiki error Sendable.”
- “Gunakan $swiftdata untuk merancang model penyimpanan.”
- “Gunakan $storekit untuk meninjau alur langganan.”

## Sumber dan versi

- [Paul Hudson / twostraws](https://github.com/twostraws/SwiftUI-Agent-Skill): SwiftUI Pro (MIT).
- [Antoine van der Lee / AvdLee](https://github.com/AvdLee/SwiftUI-Agent-Skill): SwiftUI Expert (MIT).
- [dpearson2699](https://github.com/dpearson2699/swift-ios-skills): 13 skill pelengkap (PolyForm Perimeter 1.0.0).

`skills-manifest.json` mencatat sumber dan SHA-256 setiap file snapshot. Revisi upstream yang tercatat adalah revisi yang diamati ketika ekspor, bukan jaminan revisi instalasi asli; hash snapshot adalah identitas isi yang disimpan. File skill disalin tanpa perubahan isi. Metadata paket dan salinan nested SwiftUI Pro yang menduplikasi skill utama tidak disertakan.

Koleksi ini mencakup seluruh skill Swift/iOS yang terpasang saat ekspor, bukan seluruh 86 skill yang ditawarkan upstream. Tidak ada proses pembaruan otomatis.

## Lisensi dan atribusi

Setiap skill mempertahankan lisensi sumbernya di `skills/<nama-skill>/LICENSE`, dengan salinan tambahan di `licenses/`. Tidak ada lisensi tunggal yang mengganti lisensi sumber.

Required Notice: Copyright (c) 2025 dpearson2699 (https://github.com/dpearson2699)

Materi dpearson2699 tunduk pada PolyForm Perimeter, termasuk pembatasan penyediaan produk yang bersaing. Repo ini disiapkan sebagai arsip pribadi privat. Baca lisensi masing-masing sebelum mendistribusikan atau menggunakan materi untuk tujuan lain.
