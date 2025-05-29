# 🔐 GIGO Data, Inc. – Public Archive Key (2025)

This is the official **GPG public key** used by GIGO Data, Inc. to sign daily archive files, SHA logs, and internal audit records.

- 📆 **Created on:** 2025-05-28
- 🧑‍💼 **Issued to:** Adrian Wise Santos  
- 📧 **Email:** security@gigodata.com
- 🔑 **Key Fingerprint:** `84C1 BD44 7303 BEBE 43F6  CA62 8170 3B7D 6D3F A1FD`

---

## 📥 Download

- [`GIGO_Data_Inc_Archive_Public_Key_2025.asc`](./GIGO_Data_Inc_Archive_Public_Key_2025.asc)

---

## 🛡️ How to Use

### ✅ **Verify a Signed File**

```bash
gpg --import GIGO_Data_Inc_Archive_Public_Key_2025.asc
gpg --verify SHA256_Hash_Log_2025_05_28.txt.sig SHA256_Hash_Log_2025_05_28.txt
