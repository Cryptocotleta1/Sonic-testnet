# Sonic-testnet
try to deploy smart contract to sonic testnet
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract MyContract {
    string public greeting = "Hello, Sonic Network!";

    function setGreeting(string memory _greeting) public {
        greeting = _greeting;
    }
}
