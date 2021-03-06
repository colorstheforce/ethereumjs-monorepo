[ethereumjs-client](../README.md) › ["service/lightethereumservice"](../modules/_service_lightethereumservice_.md) › [LightEthereumService](_service_lightethereumservice_.lightethereumservice.md)

# Class: LightEthereumService

Ethereum service

**`memberof`** module:service

## Hierarchy

  ↳ [EthereumService](_service_ethereumservice_.ethereumservice.md)

  ↳ **LightEthereumService**

## Index

### Constructors

* [constructor](_service_lightethereumservice_.lightethereumservice.md#constructor)

### Properties

* [chain](_service_lightethereumservice_.lightethereumservice.md#chain)
* [config](_service_lightethereumservice_.lightethereumservice.md#config)
* [flow](_service_lightethereumservice_.lightethereumservice.md#flow)
* [interval](_service_lightethereumservice_.lightethereumservice.md#interval)
* [opened](_service_lightethereumservice_.lightethereumservice.md#opened)
* [pool](_service_lightethereumservice_.lightethereumservice.md#pool)
* [running](_service_lightethereumservice_.lightethereumservice.md#running)
* [synchronizer](_service_lightethereumservice_.lightethereumservice.md#synchronizer)
* [timeout](_service_lightethereumservice_.lightethereumservice.md#timeout)

### Accessors

* [name](_service_lightethereumservice_.lightethereumservice.md#protected-name)
* [protocols](_service_lightethereumservice_.lightethereumservice.md#protocols)

### Methods

* [addListener](_service_lightethereumservice_.lightethereumservice.md#addlistener)
* [close](_service_lightethereumservice_.lightethereumservice.md#close)
* [emit](_service_lightethereumservice_.lightethereumservice.md#emit)
* [eventNames](_service_lightethereumservice_.lightethereumservice.md#eventnames)
* [getMaxListeners](_service_lightethereumservice_.lightethereumservice.md#getmaxlisteners)
* [handle](_service_lightethereumservice_.lightethereumservice.md#handle)
* [listenerCount](_service_lightethereumservice_.lightethereumservice.md#listenercount)
* [listeners](_service_lightethereumservice_.lightethereumservice.md#listeners)
* [off](_service_lightethereumservice_.lightethereumservice.md#off)
* [on](_service_lightethereumservice_.lightethereumservice.md#on)
* [once](_service_lightethereumservice_.lightethereumservice.md#once)
* [open](_service_lightethereumservice_.lightethereumservice.md#open)
* [prependListener](_service_lightethereumservice_.lightethereumservice.md#prependlistener)
* [prependOnceListener](_service_lightethereumservice_.lightethereumservice.md#prependoncelistener)
* [rawListeners](_service_lightethereumservice_.lightethereumservice.md#rawlisteners)
* [removeAllListeners](_service_lightethereumservice_.lightethereumservice.md#removealllisteners)
* [removeListener](_service_lightethereumservice_.lightethereumservice.md#removelistener)
* [setMaxListeners](_service_lightethereumservice_.lightethereumservice.md#setmaxlisteners)
* [start](_service_lightethereumservice_.lightethereumservice.md#start)
* [stop](_service_lightethereumservice_.lightethereumservice.md#stop)

## Constructors

###  constructor

\+ **new LightEthereumService**(`options`: [EthereumServiceOptions](../interfaces/_service_ethereumservice_.ethereumserviceoptions.md)): *[LightEthereumService](_service_lightethereumservice_.lightethereumservice.md)*

*Overrides [EthereumService](_service_ethereumservice_.ethereumservice.md).[constructor](_service_ethereumservice_.ethereumservice.md#constructor)*

*Defined in [lib/service/lightethereumservice.ts:11](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/lightethereumservice.ts#L11)*

Create new ETH service

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`options` | [EthereumServiceOptions](../interfaces/_service_ethereumservice_.ethereumserviceoptions.md) | constructor parameters  |

**Returns:** *[LightEthereumService](_service_lightethereumservice_.lightethereumservice.md)*

## Properties

###  chain

• **chain**: *[Chain](_blockchain_chain_.chain.md)*

*Inherited from [EthereumService](_service_ethereumservice_.ethereumservice.md).[chain](_service_ethereumservice_.ethereumservice.md#chain)*

*Defined in [lib/service/ethereumservice.ts:27](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/ethereumservice.ts#L27)*

___

###  config

• **config**: *[Config](_config_.config.md)*

*Inherited from [Service](_service_service_.service.md).[config](_service_service_.service.md#config)*

*Defined in [lib/service/service.ts:17](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/service.ts#L17)*

___

###  flow

• **flow**: *[FlowControl](_net_protocol_flowcontrol_.flowcontrol.md)*

*Inherited from [EthereumService](_service_ethereumservice_.ethereumservice.md).[flow](_service_ethereumservice_.ethereumservice.md#flow)*

*Defined in [lib/service/ethereumservice.ts:26](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/ethereumservice.ts#L26)*

___

###  interval

• **interval**: *number*

*Inherited from [EthereumService](_service_ethereumservice_.ethereumservice.md).[interval](_service_ethereumservice_.ethereumservice.md#interval)*

*Defined in [lib/service/ethereumservice.ts:28](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/ethereumservice.ts#L28)*

___

###  opened

• **opened**: *boolean*

*Inherited from [Service](_service_service_.service.md).[opened](_service_service_.service.md#opened)*

*Defined in [lib/service/service.ts:18](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/service.ts#L18)*

___

###  pool

• **pool**: *[PeerPool](_net_peerpool_.peerpool.md)*

*Inherited from [Service](_service_service_.service.md).[pool](_service_service_.service.md#pool)*

*Defined in [lib/service/service.ts:20](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/service.ts#L20)*

___

###  running

• **running**: *boolean*

*Inherited from [Service](_service_service_.service.md).[running](_service_service_.service.md#running)*

*Defined in [lib/service/service.ts:19](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/service.ts#L19)*

___

###  synchronizer

• **synchronizer**: *[LightSynchronizer](_sync_lightsync_.lightsynchronizer.md)*

*Overrides [EthereumService](_service_ethereumservice_.ethereumservice.md).[synchronizer](_service_ethereumservice_.ethereumservice.md#synchronizer)*

*Defined in [lib/service/lightethereumservice.ts:11](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/lightethereumservice.ts#L11)*

___

###  timeout

• **timeout**: *number*

*Inherited from [EthereumService](_service_ethereumservice_.ethereumservice.md).[timeout](_service_ethereumservice_.ethereumservice.md#timeout)*

*Defined in [lib/service/ethereumservice.ts:29](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/ethereumservice.ts#L29)*

## Accessors

### `Protected` name

• **get name**(): *string*

*Inherited from [EthereumService](_service_ethereumservice_.ethereumservice.md).[name](_service_ethereumservice_.ethereumservice.md#protected-name)*

*Overrides [Service](_service_service_.service.md).[name](_service_service_.service.md#protected-name)*

*Defined in [lib/service/ethereumservice.ts:50](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/ethereumservice.ts#L50)*

Service name

**`type`** {string}

**Returns:** *string*

___

###  protocols

• **get protocols**(): *[LesProtocol](_net_protocol_lesprotocol_.lesprotocol.md)[]*

*Overrides [Service](_service_service_.service.md).[protocols](_service_service_.service.md#protocols)*

*Defined in [lib/service/lightethereumservice.ts:33](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/lightethereumservice.ts#L33)*

Returns all protocols required by this service

**Returns:** *[LesProtocol](_net_protocol_lesprotocol_.lesprotocol.md)[]*

## Methods

###  addListener

▸ **addListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[addListener](_net_protocol_sender_.sender.md#addlistener)*

Defined in node_modules/@types/node/events.d.ts:62

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  close

▸ **close**(): *Promise‹void›*

*Inherited from [Service](_service_service_.service.md).[close](_service_service_.service.md#close)*

*Defined in [lib/service/service.ts:96](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/service.ts#L96)*

Close service.

**Returns:** *Promise‹void›*

___

###  emit

▸ **emit**(`event`: string | symbol, ...`args`: any[]): *boolean*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[emit](_net_protocol_sender_.sender.md#emit)*

Defined in node_modules/@types/node/events.d.ts:72

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |
`...args` | any[] |

**Returns:** *boolean*

___

###  eventNames

▸ **eventNames**(): *Array‹string | symbol›*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[eventNames](_net_protocol_sender_.sender.md#eventnames)*

Defined in node_modules/@types/node/events.d.ts:77

**Returns:** *Array‹string | symbol›*

___

###  getMaxListeners

▸ **getMaxListeners**(): *number*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[getMaxListeners](_net_protocol_sender_.sender.md#getmaxlisteners)*

Defined in node_modules/@types/node/events.d.ts:69

**Returns:** *number*

___

###  handle

▸ **handle**(`_message`: any, `_protocol`: string, `_peer`: [Peer](_net_peer_peer_.peer.md)): *Promise‹void›*

*Overrides [Service](_service_service_.service.md).[handle](_service_service_.service.md#handle)*

*Defined in [lib/service/lightethereumservice.ts:44](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/lightethereumservice.ts#L44)*

Handles incoming message from connected peer

**Parameters:**

Name | Type |
------ | ------ |
`_message` | any |
`_protocol` | string |
`_peer` | [Peer](_net_peer_peer_.peer.md) |

**Returns:** *Promise‹void›*

___

###  listenerCount

▸ **listenerCount**(`event`: string | symbol): *number*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[listenerCount](_net_protocol_sender_.sender.md#listenercount)*

Defined in node_modules/@types/node/events.d.ts:73

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |

**Returns:** *number*

___

###  listeners

▸ **listeners**(`event`: string | symbol): *Function[]*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[listeners](_net_protocol_sender_.sender.md#listeners)*

Defined in node_modules/@types/node/events.d.ts:70

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |

**Returns:** *Function[]*

___

###  off

▸ **off**(`event`: string | symbol, `listener`: function): *this*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[off](_net_protocol_sender_.sender.md#off)*

Defined in node_modules/@types/node/events.d.ts:66

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  on

▸ **on**(`event`: string | symbol, `listener`: function): *this*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[on](_net_protocol_sender_.sender.md#on)*

Defined in node_modules/@types/node/events.d.ts:63

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  once

▸ **once**(`event`: string | symbol, `listener`: function): *this*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[once](_net_protocol_sender_.sender.md#once)*

Defined in node_modules/@types/node/events.d.ts:64

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  open

▸ **open**(): *Promise‹undefined | false›*

*Inherited from [EthereumService](_service_ethereumservice_.ethereumservice.md).[open](_service_ethereumservice_.ethereumservice.md#open)*

*Overrides [Service](_service_service_.service.md).[open](_service_service_.service.md#open)*

*Defined in [lib/service/ethereumservice.ts:58](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/ethereumservice.ts#L58)*

Open eth service. Must be called before service is started

**Returns:** *Promise‹undefined | false›*

___

###  prependListener

▸ **prependListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[prependListener](_net_protocol_sender_.sender.md#prependlistener)*

Defined in node_modules/@types/node/events.d.ts:75

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  prependOnceListener

▸ **prependOnceListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[prependOnceListener](_net_protocol_sender_.sender.md#prependoncelistener)*

Defined in node_modules/@types/node/events.d.ts:76

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  rawListeners

▸ **rawListeners**(`event`: string | symbol): *Function[]*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[rawListeners](_net_protocol_sender_.sender.md#rawlisteners)*

Defined in node_modules/@types/node/events.d.ts:71

**Parameters:**

Name | Type |
------ | ------ |
`event` | string &#124; symbol |

**Returns:** *Function[]*

___

###  removeAllListeners

▸ **removeAllListeners**(`event?`: string | symbol): *this*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[removeAllListeners](_net_protocol_sender_.sender.md#removealllisteners)*

Defined in node_modules/@types/node/events.d.ts:67

**Parameters:**

Name | Type |
------ | ------ |
`event?` | string &#124; symbol |

**Returns:** *this*

___

###  removeListener

▸ **removeListener**(`event`: string | symbol, `listener`: function): *this*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[removeListener](_net_protocol_sender_.sender.md#removelistener)*

Defined in node_modules/@types/node/events.d.ts:65

**Parameters:**

▪ **event**: *string | symbol*

▪ **listener**: *function*

▸ (...`args`: any[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | any[] |

**Returns:** *this*

___

###  setMaxListeners

▸ **setMaxListeners**(`n`: number): *this*

*Inherited from [Sender](_net_protocol_sender_.sender.md).[setMaxListeners](_net_protocol_sender_.sender.md#setmaxlisteners)*

Defined in node_modules/@types/node/events.d.ts:68

**Parameters:**

Name | Type |
------ | ------ |
`n` | number |

**Returns:** *this*

___

###  start

▸ **start**(): *Promise‹void | boolean›*

*Inherited from [EthereumService](_service_ethereumservice_.ethereumservice.md).[start](_service_ethereumservice_.ethereumservice.md#start)*

*Overrides [Service](_service_service_.service.md).[start](_service_service_.service.md#start)*

*Defined in [lib/service/ethereumservice.ts:74](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/ethereumservice.ts#L74)*

Starts service and ensures blockchain is synchronized. Returns a promise
that resolves once the service is started and blockchain is in sync.

**Returns:** *Promise‹void | boolean›*

___

###  stop

▸ **stop**(): *Promise‹void | boolean›*

*Inherited from [EthereumService](_service_ethereumservice_.ethereumservice.md).[stop](_service_ethereumservice_.ethereumservice.md#stop)*

*Overrides [Service](_service_service_.service.md).[stop](_service_service_.service.md#stop)*

*Defined in [lib/service/ethereumservice.ts:86](https://github.com/ethereumjs/ethereumjs-client/blob/master/lib/service/ethereumservice.ts#L86)*

Stop service. Interrupts blockchain synchronization if its in progress.

**Returns:** *Promise‹void | boolean›*
