# ETH_Assessment
I have made my own token
In this assessement of metacraft ETH proof : beginner , I learned to create my very own Token
I have to give token name and abriveation which in this case i used my name itself so i will use string as datatype
supply number never gonna be negative so i used uint and gave initial supply of zero.

Then i mapped address with uint i want to make this public and we will be calling balances
since every address is mapped with uint so when i will give address i will be getting tokenamount that that address has.

i have mint function that have parametrs Address and Value
the function will increase the total supply by that number and increases the balance of the address by that amount

My contract have burn function which is just opposite of mint function as it will destroy tokens
it will have address and value and deduct the value and balance of the address
