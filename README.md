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
    address private _owner;_0x0.....

    event OwnershipTransferred(address indexed previousOwner, address indexed newOwner);_

      uint256 private constant _NOT_ENTERED = 1;
    uint256 private constant _ENTERED = 2;

    uint256 private _status;

    constructor() {
        _status = _NOT_ENTERED;
    }
