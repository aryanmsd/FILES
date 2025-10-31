// SPDX-License-Identifier: MIT
pragma solidity >=0.5.17;

contract Counter {
    uint256 public count = 0;

    function increment() public {
        count += 1;
    }

    function getCount() public view returns (uint256) {
        return count;
    }
}
