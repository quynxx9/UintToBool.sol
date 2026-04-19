# UintToBool.sol
UintToBool.sol
pragma solidity ^0.8.20;
contract UintToBool {
    function convert(uint x) public pure returns(bool){
        return x != 0;
    }
}
