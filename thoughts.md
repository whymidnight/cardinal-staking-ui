# thoughta

## hardcoded configuration

```javascript
const oracle = new PublicKey("oracle");
const rewardAuthority = new PublicKey("rewardAuthority");

const configuration = {
  ["stake_pool_0"]: {
    rewardDistributors: [
      {
        rewardMint: new PublicKey("shitcoin0"),
        rewardDistributorPda,
        distributorIndex: 0,
      },
      {
        rewardMint: new PublicKey("shitcoin1"),
        rewardDistributorPda,
        distributorIndex: 1,
      },
      {
        rewardMint: new PublicKey("shitcoin2"),
        rewardDistributorPda,
        distributorIndex: 2,
      },
    ]
  },
  ["stake_pool_1"]: {
    rewardDistributors: [
      {
        rewardMint: new PublicKey("shitcoin0"),
        rewardDistributorPda,
        distributorIndex: 0,
      },
      {
        rewardMint: new PublicKey("shitcoin1"),
        rewardDistributorPda,
        distributorIndex: 1,
      },
      {
        rewardMint: new PublicKey("shitcoin2"),
        rewardDistributorPda,
        distributorIndex: 2,
      },
    ]
  }
};
```
