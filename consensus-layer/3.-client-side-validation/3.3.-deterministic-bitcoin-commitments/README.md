# 3.3. Deterministic bitcoin commitments

Deterministic bitcoin commitments (DBC) provide a way to create a provably unique commitments inside bitcoin transactions. RGB protocol allows two types of DBC: based on taproot outputs (so-called “**tapret**”) and based on `OP_RETURN` outputs (so-called “**opret**”), useful for old hardware which doesn’t support taproot.
