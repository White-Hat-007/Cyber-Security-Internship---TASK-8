# Privacy and Leak Test Audit ✅

## 🌐 Overview
This document outlines the test results of VPN effectiveness, encryption, and DNS/WebRTC leak protection using **ProtonVPN** on Windows.

---

## 🔐 VPN Connection Details

- **VPN Provider**: ProtonVPN
- **Server Used**: Netherlands (NL-FREE#30)
- **Protocol**: WireGuard (UDP)
- **Assigned VPN IP**: `185.177.125.65`
- **Original IP**: `45.251.33.201`

---

## 🧪 VPN Encryption and Privacy Features - Test Summary

### ✅ WebRTC Leak Test
- **Result**: No IP leaks detected
- **Local IP**: Hidden
- **Public IP**: VPN IP only

### ✅ DNS Leak Test
- **DNS Servers**: `Datacamp Limited` (USA)
- **Location Leaked**: No
- **Number of DNS Servers**: 4 (ProtonVPN default)

### ✅ TLS and Encryption Test (via Cloudflare)
- **TLS Version**: TLS 1.3
- **DNSSEC**: Enabled
- **ESNI/Encrypted SNI**: Supported by browser
- **Conclusion**: Encrypted and private

---

## 🔎 VPN Benefits

- 🔒 Full traffic encryption
- 🛡️ IP masking to prevent tracking
- 🚫 Bypasses censorship and geo-blocks
- 📉 Reduces ISP throttling
- 🧅 Supports advanced privacy (WireGuard, Tor, Secure Core*)

---

## ⚠️ VPN Limitations

- ❌ Some DNS servers still US-based
- 🔍 Fingerprinting still possible
- 📍 Login challenges on geo-sensitive sites
- 🐌 Speed may degrade during peak usage
- 💵 Secure Core require premium

---

## 📌 Recommendation

For maximum privacy:
1. Use Secure Core or multi-hop (premium).
2. Use privacy-focused browser (Brave/Firefox + hardened settings).
3. Enable kill switch and IPv6 block.
4. Avoid WebRTC leaks by disabling in browser (or use uBlock Origin).
5. Avoid logging into identifiable accounts when anonymity is required.

---

## 📈 VPN OFF vs. VPN ON

| Feature         | VPN ON (ProtonVPN)      | VPN OFF (Direct ISP)     |
|-----------------|--------------------------|---------------------------|
| IP Masked       | ✅ Yes                    | ❌ No                     |
| WebRTC Leaks    | ❌ No Leak                | ⚠️ Possible               |
| DNS Leaks       | ❌ No                     | ⚠️ ISP-visible            |
| TLS 1.3 Support | ✅ Yes                    | Depends on browser        |
| Speed           | ⚠️ Slightly Reduced       | ✅ Full ISP Bandwidth     |

---

> **NOTE**: All tests were performed using [BrowserLeaks.com](https://browserleaks.com) and [Cloudflare's ESNI tool](https://www.cloudflare.com/ssl/encrypted-sni/).

---

## 👨‍💻 Author

**Darsh Chatrani**  
🔗 [LinkedIn](https://linkedin.com/in/darshchatrani)  
📞 Contact: +91 97899 57123

---
