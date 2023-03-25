// SPDX-License-Identifier: MIT
pragma solidity ^0.8.9;

import "@openzeppelin/contracts@4.8.2/token/ERC20/ERC20.sol";

contract Zolotarevych is ERC20 {
    constructor() ERC20("Zolotarevych", "ZLT") {
        _mint(msg.sender, 1000000 * 10 ** decimals());
    }

    function forBuyer() external payable {
        uint256 tokAway = msg.value * 10;
        _mint(msg.sender, tokAway * 10 ** decimals());
    }
}
