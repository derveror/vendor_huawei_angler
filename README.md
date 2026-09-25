# Proprietary files for Google Nexus 6P (angler)

This tree is generated from official Google OPM7.181205.001 inputs. Every admitted source file is byte-identical to the factory image. Most are covered by the official Huawei vendor-image package or an explicit Qualcomm extraction path. Six closure files (two libaudcal and four camera libraries) are factory-only because the same paths in the Huawei package contain different bytes; their provenance is recorded explicitly. The ISP module is regenerated from the exact stock input with a scoped Android P mutex/FORTIFY instruction fix whose upstream provenance is pinned in the metadata.

Huawei archive SHA-256: `2eb9a77de059739d33c7fad07e34034f03a93d70eea39460bb0d9278e5763053`.

Qualcomm archive SHA-256: `78222d6c627020d8312477f647253b37569882ebdfe527207f39074dc05fc6a1`.

`BLOB_PROVENANCE.tsv` records source/destination paths, SHA-256, size, file type, ELF identity, license provenance, and any scoped output fixup. License acceptance for local extraction does not authorize unrestricted public redistribution; do not push proprietary bytes until that policy is reviewed separately.
