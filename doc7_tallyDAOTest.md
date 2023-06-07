tally is the most standard governance as we researched.
we want to test tally whether if we can upgrade the governance itself or not.

well I tried to build an ERC20 token first and then governance in here : https://wizard.openzeppelin.com/#governor

I deployed the simple votable token and then upgradeable governor in hardhat.

then I tried to add the governor in tally : https://www.tally.xyz/add-a-dao/governor

in the first try it could not add the governor but when I added start blocks it finally found the governor.

then I tried to get the governor version(my custom version getter function) and it returned `1`.

