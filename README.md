# AddressStore.sol
Such a thoughtful take here.
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract AddressStore {
    address public lastSender;

    function updateSender() public {
        lastSender = msg.sender;
    }
}
Add new feature
Improve error handling
