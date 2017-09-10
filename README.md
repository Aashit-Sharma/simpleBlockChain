# simpleBlockChain


#How to run it 

import block
my_block = block.Block('some data')
my_block
Block<Hash: 4df705..., Nonce: None>
my_block.mine()
my_block
Block<Hash: 00006a..., Nonce: 3763>
import block
import block-chain


chain = blockchain.Block-chain()


first = block.Block('first')
second = block.Block('second')
third = block.Block('third')

chain.add_block(first)
chain.add_block(second)
chain.add_block(third)

first.update_data('broken chain')

print(chain.broken)  # True

chain.repair()

print(chain.broken)  # False
