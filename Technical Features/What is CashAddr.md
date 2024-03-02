[CashAddr](https://reference.cash/protocol/blockchain/encoding/cashaddr/) is an address format introduced by Bitcoin Cash in 2018 to address confusion with the legacy address encoding used by BTC. The key features of CashAddr include:

#### Distinct Format:

* Legacy Format (BTC): 1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa
* CashAddr Format (Bitcoin Cash): bitcoincash:qp3wjpa3tjlj042z2wv7hahsldgwhwy0rq9sywjpyy

#### Enhanced User Experience:

* CashAddr aims to improve ease of use when copying and sharing payment information.
* The format includes a human-readable prefix, making it more user-friendly and recognizable.

#### Preventing Confusion:

* The primary motivation behind CashAddr is to prevent users from accidentally sending Bitcoin Cash to BTC addresses or vice versa.
* It helps avoid potential cross-chain transaction errors by providing a clear visual distinction between BTC and Bitcoin Cash addresses.

#### Based on Bech32 Work:

* CashAddr encoding is based on the Bech32 work, offering advantages such as strong checksums, efficient QR code encoding, and improved speed for address encoding and decoding.

#### Commitment to User-Friendly Design:

* The introduction of CashAddr reflects the Bitcoin Cash community's commitment to improving user experience and making Bitcoin Cash more accessible to a broader audience.

In summary, CashAddr is a user-friendly address format for Bitcoin Cash that not only provides a clear visual distinction from Bitcoin addresses but also incorporates features for efficient encoding, decoding, and prevention of cross-chain transaction errors.

Learn more about CashAddr and other Bitcoin Cash technical features in our [broad exploration of Bitcoin Cash upgrades](https://bchfaq.com/what-is-the-difference-between-bitcoin-and-bitcoin-cash-part-4/#bitcoin-cash-upgrades).