# Seam DAO

The Seam Dao will evolve to have the following main responsibilities


## Staking + yield protocol management
    -adjust lending markets, DEXs integrated with composed pools
    - alter fees imposed on staking, and sale of staked position

## Support the network with additional validators
    -creation of dashboard validator tooling
    - deploy validators to earn validator fees + stake fees

## Treasury allocation
The Dao will be resposible for selecting the quantity and validators to delegate a portion of the treasury up to 30%. From here the dao can either hold this staked position, or mint conditional contracts off the staked deposit.
- vote on the staking duration and validators of funds in the treasury
- While the stake is locked, the can vote on minting and selling 'close postions' on previous minted and sold conditionals which conditions have been made valid, making them potential loss taking positions for the DAO.
  - for example if APT=2 USD(via an oracle) the dao stakes 100k apt and sells a conditional contract for the right to 10k APT staked(+stake yield) if APT>2.50 USD. lets say this was sold for 1k USD(500 APT)
  - situation 1: suppose that APT hits 2.50, now for every cent of movement of APT, the contract is worth 10$ more. It is now in the DAOs interest to purchase the soonest to expiration conditional(s) with a strike out of the money. This is an oversimplification and the dao could have reason to purchase contract with a further expiry if the premium is lower.
  