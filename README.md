# mastershop-licences

Public revocation list of MasterShop-OS licences (`revoked.json`).

It holds only SHA-256 fingerprints (no customer names, codes or machine IDs) and is signed with the vendor's key;
MasterShop-OS checks the signature and keeps the newest list it has seen. Written by the MasterShop-OS KeyGen (`publish`).
