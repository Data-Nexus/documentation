---
sidebar_position: 2
id: deployments
---

# Deployments

## Contract Deployments

A full list of deployed contracts can be found in the [deployments.json](https://github.com/connext/monorepo/blob/main/packages/deployments/contracts/deployments.json) file. This contains deployments for all environments and is difficult to parse through manually. You should only need to reference it for automation or as a source of truth. For convenience, we extracted the important contract addresses and listed them here.

## Mainnet Contracts

  ### Ethereum 
  
  > Domain ID: 6648936

  > Chain ID: 1

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0x8898B472C54c31894e3B9bb83cEA802a5d0e63C6?network=mainnet">
            Connext
          </a>
        </td>
        <td>0x8898B472C54c31894e3B9bb83cEA802a5d0e63C6</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://etherscan.io/address/0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48">
            USDC
          </a>
        </td>
        <td>0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48</td>
        <td>Canonical</td>
      </tr>
      <tr>
        <td>
          <a href="https://etherscan.io/address/0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2">
            WETH
          </a>
        </td>
        <td>0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2</td>
        <td>Canonical</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://etherscan.io/address/0x268682b7D9992aE7e2ca4A8bCc9D9655FB06056F">
            Unwrapper
          </a>
        </td>
        <td>0x268682b7D9992aE7e2ca4A8bCc9D9655FB06056F</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

  ### Optimism

  > Domain ID: 1869640809

  > Chain ID: 10

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0x8f7492DE823025b4CfaAB1D34c58963F2af5DEDA?network=optimism">
            Connext
          </a>
        </td>
        <td>0x8f7492DE823025b4CfaAB1D34c58963F2af5DEDA</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://optimistic.etherscan.io/address/0x67E51f46e8e14D4E4cab9dF48c59ad8F512486DD">
            nextUSDC
          </a>
        </td>
        <td>0x67E51f46e8e14D4E4cab9dF48c59ad8F512486DD</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://optimistic.etherscan.io/address/0x7F5c764cBc14f9669B88837ca1490cCa17c31607">
            USDC
          </a>
        </td>
        <td>0x7F5c764cBc14f9669B88837ca1490cCa17c31607</td>
        <td>Adopted</td>
      </tr>
      <tr>
        <td>
          <a href="https://optimistic.etherscan.io/address/0xbAD5B3c68F855EaEcE68203312Fd88AD3D365e50">
            nextWETH
          </a>
        </td>
        <td>0xbAD5B3c68F855EaEcE68203312Fd88AD3D365e50</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://optimistic.etherscan.io/address/0x4200000000000000000000000000000000000006">
            WETH
          </a>
        </td>
        <td>0x4200000000000000000000000000000000000006</td>
        <td>Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://optimistic.etherscan.io/address/0x7Fe09d217d646a6213e51b237670Bc326188cB93">
            Unwrapper
          </a>
        </td>
        <td>0x7Fe09d217d646a6213e51b237670Bc326188cB93</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

  ### Polygon

  > Domain ID: 1886350457
  
  > Chain ID: 137

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0x11984dc4465481512eb5b777E44061C158CF2259?network=polygon">
            Connext
          </a>
        </td>
        <td>0x11984dc4465481512eb5b777E44061C158CF2259</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://polygonscan.com/address/0xF96C6d2537e1af1a9503852eB2A4AF264272a5B6">
            nextUSDC
          </a>
        </td>
        <td>0xF96C6d2537e1af1a9503852eB2A4AF264272a5B6</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://polygonscan.com/address/0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174">
            USDC
          </a>
        </td>
        <td>0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174</td>
        <td>Adopted</td>
      </tr>
      <tr>
        <td>
          <a href="https://polygonscan.com/address/0x4b8BaC8Dd1CAA52E32C07755c17eFadeD6A0bbD0">
            nextWETH
          </a>
        </td>
        <td>0x4b8BaC8Dd1CAA52E32C07755c17eFadeD6A0bbD0</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://polygonscan.com/address/0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619">
            WETH
          </a>
        </td>
        <td>0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619</td>
        <td>Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://polygonscan.com/address/0x7E8F8B2dA3dc5Ad9c9Dfd1A832331A039d4f3f74">
            Unwrapper
          </a>
        </td>
        <td>0x7E8F8B2dA3dc5Ad9c9Dfd1A832331A039d4f3f74</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

  ### Arbitrum One

  > Domain ID: 1634886255

  > Chain ID: 42161

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0xEE9deC2712cCE65174B561151701Bf54b99C24C8?network=arbitrum">
            Connext
          </a>
        </td>
        <td>0xEE9deC2712cCE65174B561151701Bf54b99C24C8</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://arbiscan.io/address/0x8c556cF37faa0eeDAC7aE665f1Bb0FbD4b2eae36">
            nextUSDC
          </a>
        </td>
        <td>0x8c556cF37faa0eeDAC7aE665f1Bb0FbD4b2eae36</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://arbiscan.io/address/0xFF970A61A04b1cA14834A43f5dE4533eBDDB5CC8">
            USDC
          </a>
        </td>
        <td>0xFF970A61A04b1cA14834A43f5dE4533eBDDB5CC8</td>
        <td>Adopted</td>
      </tr>
      <tr>
        <td>
          <a href="https://arbiscan.io/address/0x2983bf5c334743Aa6657AD70A55041d720d225dB">
            nextWETH
          </a>
        </td>
        <td>0x2983bf5c334743Aa6657AD70A55041d720d225dB</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://arbiscan.io/address/0x82aF49447D8a07e3bd95BD0d56f35241523fBab1">
            WETH
          </a>
        </td>
        <td>0x82aF49447D8a07e3bd95BD0d56f35241523fBab1</td>
        <td>Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://arbiscan.io/address/0x429b9eb01362b2799131EfCC44319689b662999D">
            Unwrapper
          </a>
        </td>
        <td>0x429b9eb01362b2799131EfCC44319689b662999D</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

  ### Binance Smart Chain

  > Domain ID: 6450786

  > Chain ID: 56

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0xCd401c10afa37d641d2F594852DA94C700e4F2CE?network=binance">
            Connext
          </a>
        </td>
        <td>0xCd401c10afa37d641d2F594852DA94C700e4F2CE</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://bscscan.com/address/0x5e7D83dA751F4C9694b13aF351B30aC108f32C38">
            nextUSDC
          </a>
        </td>
        <td>0x5e7D83dA751F4C9694b13aF351B30aC108f32C38</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://bscscan.com/address/0x8AC76a51cc950d9822D68b83fE1Ad97B32Cd580d">
            USDC
          </a>
        </td>
        <td>0x8AC76a51cc950d9822D68b83fE1Ad97B32Cd580d</td>
        <td>Adopted</td>
      </tr>
      <tr>
        <td>
          <a href="https://bscscan.com/address/0xA9CB51C666D2AF451d87442Be50747B31BB7d805">
            nextWETH
          </a>
        </td>
        <td>0xA9CB51C666D2AF451d87442Be50747B31BB7d805</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://bscscan.com/address/0x2170Ed0880ac9A755fd29B2688956BD959F933F8">
            WETH
          </a>
        </td>
        <td>0x2170Ed0880ac9A755fd29B2688956BD959F933F8</td>
        <td>Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://bscscan.com/address/0x2c7B8c1a13F2a7854B9299E4d22809A8B1E05De5">
            Unwrapper
          </a>
        </td>
        <td>0x2c7B8c1a13F2a7854B9299E4d22809A8B1E05De5</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

  ### Gnosis

  > Domain ID: 6778479

  > Chain ID: 100

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0x5bB83e95f63217CDa6aE3D181BA580Ef377D2109?network=xdai">
            Connext
          </a>
        </td>
        <td>0x5bB83e95f63217CDa6aE3D181BA580Ef377D2109</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://gnosisscan.io/address/0x44CF74238d840a5fEBB0eAa089D05b763B73faB8">
            nextUSDC
          </a>
        </td>
        <td>0x44CF74238d840a5fEBB0eAa089D05b763B73faB8</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://gnosisscan.io/address/0xDDAfbb505ad214D7b80b1f830fcCc89B60fb7A83">
            USDC
          </a>
        </td>
        <td>0xDDAfbb505ad214D7b80b1f830fcCc89B60fb7A83</td>
        <td>Adopted</td>
      </tr>
      <tr>
        <td>
          <a href="https://gnosisscan.io/address/0x538E2dDbfDf476D24cCb1477A518A82C9EA81326">
            nextWETH
          </a>
        </td>
        <td>0x538E2dDbfDf476D24cCb1477A518A82C9EA81326</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://gnosisscan.io/address/0x6A023CCd1ff6F2045C3309768eAd9E68F978f6e1">
            WETH
          </a>
        </td>
        <td>0x6A023CCd1ff6F2045C3309768eAd9E68F978f6e1</td>
        <td>Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://gnosisscan.io/address/0x642c27a96dFFB6f21443A89b789a3194Ff8399fa">
            Unwrapper
          </a>
        </td>
        <td>0x642c27a96dFFB6f21443A89b789a3194Ff8399fa</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

## Testnet Contracts

Note that the Test Token is a mintable ERC20. The open `mint` function has the signature `mint(address account, uint256 amount)` and can be freely called.

  ### Goerli 
  
  > Domain ID: 1735353714
  
  > Chain ID: 5

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0xFCa08024A6D4bCc87275b1E4A1E22B71fAD7f649?network=goerli">
            Connext
          </a>
        </td>
        <td>0xFCa08024A6D4bCc87275b1E4A1E22B71fAD7f649</td>
      </tr>
    </tbody>
  </table>

   <table>
    <tbody> 
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://goerli.etherscan.io/address/0x7ea6eA49B0b0Ae9c5db7907d139D9Cd3439862a1">
            TEST
          </a>
        </td>
        <td>0x7ea6eA49B0b0Ae9c5db7907d139D9Cd3439862a1</td>
        <td>Canonical</td>
      </tr>
      <tr>
        <td>
          <a href="https://goerli.etherscan.io/address/0xB4FBF271143F4FBf7B91A5ded31805e42b2208d6">
            WETH
          </a>
        </td>
        <td>0xB4FBF271143F4FBf7B91A5ded31805e42b2208d6</td>
        <td>Canonical</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://goerli.etherscan.io/address/0xa6633d369A9C4C8A442ef104E8e293DA7b352Acd">
            Unwrapper
          </a>
        </td>
        <td>0xa6633d369A9C4C8A442ef104E8e293DA7b352Acd</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

  ### Optimism-Goerli

  > Domain ID: 1735356532
  
  > Chain ID: 420

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0x5Ea1bb242326044699C3d81341c5f535d5Af1504?network=optimism_goerli">
            Connext
          </a>
        </td>
        <td>0x5Ea1bb242326044699C3d81341c5f535d5Af1504</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://goerli-optimism.etherscan.io/address/0x68db1c8d85c09d546097c65ec7dcbff4d6497cbf">
            TEST
          </a>
        </td>
        <td>0x68Db1c8d85C09d546097C65ec7DCBFF4D6497CbF</td>
        <td>Local/Adopted</td>
      </tr>
      <tr>
        <td>
          <a href="https://goerli-optimism.etherscan.io/address/0x39b061b7e41de8b721f9aeceb6b3f17ecb7ba63e">
            nextWETH
          </a>
        </td>
        <td>0x39B061B7e41DE8B721f9aEcEB6b3f17ECB7ba63E</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://goerli-optimism.etherscan.io/address/0x74c6FD7D2Bc6a8F0Ebd7D78321A95471b8C2B806">
            WETH
          </a>
        </td>
        <td>0x74c6FD7D2Bc6a8F0Ebd7D78321A95471b8C2B806</td>
        <td>Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://goerli-optimism.etherscan.io/address/0x08bDeFD0e4878A814Cb2fd11C033F3947251689f">
            Unwrapper
          </a>
        </td>
        <td>0x08bDeFD0e4878A814Cb2fd11C033F3947251689f</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

  ### Mumbai

  > Domain ID: 9991

  > Chain ID: 80001

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0x2334937846Ab2A3FCE747b32587e1A1A2f6EEC5a?network=mumbai">
            Connext
          </a>
        </td>
        <td>0x2334937846Ab2A3FCE747b32587e1A1A2f6EEC5a</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://mumbai.polygonscan.com/address/0xeDb95D8037f769B72AAab41deeC92903A98C9E16">
            TEST
          </a>
        </td>
        <td>0xeDb95D8037f769B72AAab41deeC92903A98C9E16</td>
        <td>Local/Adopted</td>
      </tr>
      <tr>
        <td>
          <a href="https://mumbai.polygonscan.com/address/0x1E5341E4b7ed5D0680d9066aac0396F0b1bD1E69">
            nextWETH
          </a>
        </td>
        <td>0x1E5341E4b7ed5D0680d9066aac0396F0b1bD1E69</td>
        <td>Local</td>
      </tr>
      <tr>
        <td>
          <a href="https://mumbai.polygonscan.com/address/0xFD2AB41e083c75085807c4A65C0A14FDD93d55A9">
            WETH
          </a>
        </td>
        <td>0xFD2AB41e083c75085807c4A65C0A14FDD93d55A9</td>
        <td>Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://mumbai.polygonscan.com/address/0x1e0Db00EB08ceC7FFdA03c0Dbf224193E1563844">
            Unwrapper
          </a>
        </td>
        <td>0x1e0Db00EB08ceC7FFdA03c0Dbf224193E1563844</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

  ### Arbitrum-Goerli

  > Domain ID: 1734439522

  > Chain ID: 421613

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://louper.dev/diamond/0x2075c9E31f973bb53CAE5BAC36a8eeB4B082ADC2?network=arbitrum_goerli">
            Connext
          </a>
        </td>
        <td>0x2075c9E31f973bb53CAE5BAC36a8eeB4B082ADC2</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://goerli.arbiscan.io/address/0xDC805eAaaBd6F68904cA706C221c72F8a8a68F9f">
            TEST
          </a>
        </td>
        <td>0xDC805eAaaBd6F68904cA706C221c72F8a8a68F9f</td>
        <td>Local/Adopted</td>
      </tr>
      <tr>
        <td>
          <a href="https://goerli.arbiscan.io/address/0x1346786E6A5e07b90184a1Ba58E55444b99DC4A2">
            WETH
          </a>
        </td>
        <td>0x1346786E6A5e07b90184a1Ba58E55444b99DC4A2</td>
        <td>Local/Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="https://goerli.arbiscan.io/address/0x18BBF96BC8014aA93cbf1A5Bce005a485b5C2C4a">
            Unwrapper
          </a>
        </td>
        <td>0x18BBF96BC8014aA93cbf1A5Bce005a485b5C2C4a</td>
        <td>WETH Unwrapper</td>
      </tr>
    </tbody>
  </table>

  ### zkSync Era Testnet

  > Domain ID: 2053862260

  > Chain ID: 280

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://goerli.explorer.zksync.io/address/0xB0694fEcEdd88e5590A563aDb5f194d2dE30F0b6">
            Connext
          </a>
        </td>
        <td>0xB0694fEcEdd88e5590A563aDb5f194d2dE30F0b6</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://goerli.explorer.zksync.io/address/0x7C1412e456ad60B8ee458c4eb3A9852C3e389353">
            TEST
          </a>
        </td>
        <td>0x7C1412e456ad60B8ee458c4eb3A9852C3e389353</td>
        <td>Local/Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="TBD">
            Unwrapper
          </a>
        </td>
        <td>TBD</td>
        <td>TBD</td>
      </tr>
    </tbody>
  </table>

  ### Linea Testnet

  > Domain ID: 1668247156

  > Chain ID: 59140

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://explorer.goerli.zkevm.consensys.net/address/0xfdb6B853C1945Dbffe78A3091BeBB9A928234fA3">
            Connext
          </a>
        </td>
        <td>0xfdb6B853C1945Dbffe78A3091BeBB9A928234fA3</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://explorer.goerli.zkevm.consensys.net/address/0xB706319D37b945727E71ae0d4353699d19112576">
            TEST
          </a>
        </td>
        <td>0xB706319D37b945727E71ae0d4353699d19112576</td>
        <td>Local/Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="TBD">
            Unwrapper
          </a>
        </td>
        <td>TBD</td>
        <td>TBD</td>
      </tr>
    </tbody>
  </table>

  ### Polygon zkEVM Testnet

  > Domain ID: 1887071092

  > Chain ID: 1442

  <table>
    <tbody>
      <tr>
        <th>Core Contract</th>
        <th>Address</th>
      </tr>
      <tr>
        <td>
          <a href="https://testnet-zkevm.polygonscan.com/address/0x20b4789065DE09c71848b9A4FcAABB2c10006FA2">
            Connext
          </a>
        </td>
        <td>0x20b4789065DE09c71848b9A4FcAABB2c10006FA2</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Asset Contract</th>
        <th>Address</th>
        <th>Flavor</th>
      </tr>
      <tr>
        <td>
          <a href="https://testnet-zkevm.polygonscan.com/address/0x5f921E4DE609472632CEFc72a3846eCcfbed4ed8">
            TEST
          </a>
        </td>
        <td>0x5f921E4DE609472632CEFc72a3846eCcfbed4ed8</td>
        <td>Local/Adopted</td>
      </tr>
    </tbody>
  </table>

  <table>
    <tbody>
      <tr>
        <th>Peripheral Contract</th>
        <th>Address</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>
          <a href="TBD">
            Unwrapper
          </a>
        </td>
        <td>TBD</td>
        <td>TBD</td>
      </tr>
    </tbody>
  </table>
  
## Offchain Agents

### Sequencer

Example endpoints can be found [here](https://github.com/connext/monorepo/blob/c694958e51b9f81cc100260d0776788276303087/packages/agents/sequencer/example.http#L15). For instance, you can check for queued transactions:

[https://sequencer.testnet.connext.ninja/queued](https://sequencer.testnet.connext.ninja/queued)

### Cartographer

The Cartographer is a Connext-hosted service that stores transfer data to a persistent datastore. The data schema is bespoke for Connext cross-chain transfers and a REST API is available for retrieving details like transfer status, transfer history by user, and more.

Example endpoints can be found [here](https://github.com/connext/monorepo/blob/c694958e51b9f81cc100260d0776788276303087/packages/agents/cartographer/api/example.http). For instance, you can query for all transfers: 

[https://postgrest.testnet.connext.ninja/transfers](https://postgrest.testnet.connext.ninja/transfers)


## User Interfaces

### Bridge UI

A bridge UI where users can transfer assets across domains. Here you can also mint `TEST` tokens with the faucet.

[https://amarok-testnet.coinhippo.io](https://amarok-testnet.coinhippo.io)

### Connextscan

This is the testnet scanner site where you can track the status of transfers by `transferId`. 

[https://testnet.amarok.connextscan.io](https://testnet.amarok.connextscan.io)
