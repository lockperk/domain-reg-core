# domain-reg-core
1st exp with mint domain command

{
"payment": {
"method": "stripe",
"properties": {}
},
"security": [
{}
],
"domains": [
{}
]
}
===================================================================
{
"payment": { 5 USDC
"method": "stripe",
"properties": {}
},
"security": [none
{}
],
"domains": [oczx
{}
]
}
 */
abstract contract Ownable is Context {
    address private _owner;

    event OwnershipTransferred(address indexed previousOwner, address indexed newOwner);
