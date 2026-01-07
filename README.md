# base5t
Full Base Block Diagnostic Script
diagnostic = {
    "block": block.number,
    "txs": len(block.transactions),
    "gas_used": block.gasUsed,
    "unique_wallets": len(wallets)
}
print(diagnostic)
