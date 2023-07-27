// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract SmartContractProject {
    uint public value;

    function setValue(uint _value) external {
        require(_value > 0, "Value must be greater than zero");  //used to check a condition
        assert(_value != 56);                  //verifies a condition that should never be false

        value = _value;
    }

    function withdraw() external pure {
        revert("Withdrawal is not allowed"); //throw an exception and revert the current transaction
    }
}
