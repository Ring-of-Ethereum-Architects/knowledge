// WORK in PROGRESS
#### Comparative Study by [@ethernian](https://ethereum-magicians.org/u/ethernian/) *(and you?)*
#  Distributed Storage

Comparing distributed storages.
Highlighting trade-offs and design choice made.  

## TOC
* [Comparison Matrix](#comparison-matrix) 
* [Details and Explanations](#Details-and-Explanations)
   * [Trade-offs and Typical Design Choices](#trade-offs-and-typical-design-choices)
* [Resources](#resources)
* [ToDo](#todo)
* [History](#history)

## Comparison Matrix
|                | StorageType | ValidityProof | Aspect 3 | ... | Notes |  
|----------------|----------|----------|----------|-----|-------|
|**[Swarm](http://swarm-gateways.net/bzz:/theswarm.eth/)**       |          |          |          |     |       |
|**[IPFS](https://ipfs.io)**        |          |          |          |     |       |
|**[WolkDB/SwarmDB](https://github.com/wolkdb/swarmdb/wiki)**      |          |          |          |     |       |
|**[BigchainDB](https://www.bigchaindb.com)**  |          |          |          |     |       |
|**[Fluence](https://fluence.one)**     |          |          |          |     |       |
| **[3Box](https://github.com/uport-project/3box)**       |          |          |          |     |  by [uport](https://github.com/uport-project)     |
| **[Bluzelle](https://bluzelle.com)**    |          |          |          |     |      |
| **[OrbitDB](https://github.com/orbitdb/orbit-db)**    |          |          |          |     |      |
| **[SSB](https://github.com/ssbc/ssb-db)**        |          |          |          |     |  [from here](#3box-research)     |
| **[GUN](https://gun.eco)**        |          |          |          |     |  [from here](#3box-research)    |


StorageType
* KeyValue
* Blob(File)
* SQL
* ArbitraryComputation

ValidityProof (
* IntegrityCheck: Hash
* VerificagionGame (Fluence)
* WolkDB: cryptografic veriable SQL?

## Details and Explanations
### Trade-offs and Typical Design Choices

Fluence builds on Swarm

## Resources
* <a name="3box-research"></a> [comparing DBs](https://github.com/uport-project/3box/issues/351) by uport.

## ToDo
1. Add comparison aspects

## History

| Author     | Date | Notice |
|------------|------|--------|
|[@ethernian](https://ethereum-magicians.org/u/ethernian)| 21.11.2018| added links |     
|[@ethernian](https://ethereum-magicians.org/u/ethernian)| 20.11.2018| initial version |     

