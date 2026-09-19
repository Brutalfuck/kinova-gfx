# Kinova GFX — Server Files (GitHub)

Ye repo app ka poora server hai. Sab files yahan se load hoti hain.

## File kaam kya karti hai

| File | Kaam |
|---|---|
| app_config.json | App settings — telegram links, title, logo |
| gfx_configs.json | GFX presets list (app mein dikhta hai) |
| domain_filters.json | VPN ke extra block/allow domains |
| filters.json | VPN ki main filter list (43KB, pehle se bhari hui) |
| firewall_rules.json | VPN on/off flag (is_active) |
| app_updates.json | Update check — naya version notify |
| broadcasts.json | Announcements (abhi khaali) |
| verify_license.json | App ka "license valid" jawaab (hamesha active) |
| fps/apply | FPS patch lagane ka jawaab — pak file ka link yahan |
| fps/remove_config | FPS patch hatane ka jawaab |
| files/ | Tumhari .pak files + patches yahan upload karo |

## Naya version release karna ho to
1. Naya APK banao/lo
2. GitHub repo -> Releases -> "Draft a new release" -> tag: v1.1
3. APK file ko release mein upload karo
4. app_updates.json kholo:
   - version_code: 460 se badha do (461)
   - version_name: nayi version
   - changelog: kya naya hai
   - download_url: nayi release ka APK link
5. Commit karo — bas! Purane users ko update popup dikhega

## Telegram change karna ho to
app_config.json mein telegram_link_1 aur telegram_link_2 badlo.

## VPN domain block karna ho to
domain_filters.json mein add karo:
[{"domain": "example.com", "type": "block"}]
