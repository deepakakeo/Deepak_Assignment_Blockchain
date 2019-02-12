I am using Block.io for getting balance and addresses.

First we need the API KEY and SECRET PIN. We get it from "block.io"

1. Install block.io Python package

pip install block-io==1.1.9


2. Go to the Python shell 

>> from block_io import BlockIo
>> version = 2 								# API version
>> block_io = BlockIo('YOUR API KEY', 'SECRET PIN', version)

3. To get balance

>> block_io.get_address_balance('Address')