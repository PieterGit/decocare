### MIDNIGHTS analysis/bewest-pump/ReadHistoryData-page-26.data.list_opcodes.markdown: 4
## START logs/ReadHistoryData-page-26.data
#### STOPPING DOUBLE NULLS @ 1018, found 4 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0xf7 0x12                                  ..
##### DEBUG DECIMAL
            247   18
#### RECORD 0 Bolus 2012-10-19T19:47:40 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.7, 'dual_component': '??', 'programmed': 2.7, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x1b 0x1b 0x00                        ....
    decimal
              1   27   27    0
    datetime (2012-10-19T19:47:40)
    0000   0xa8 0xaf 0x53 0x13 0x0c                   ..S..
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 1 CalBGForPH 2012-10-19T20:52:14 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 197}
```
    op hex (2)
    0000   0x0a 0xc5                                  ..
    decimal
             10  197
    datetime (2012-10-19T20:52:14)
    0000   0x8e 0xb4 0x34 0x13 0x0c                   ..4..
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 2 BolusWizard 2012-10-19T20:52:37 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 16,
 '_byte[7]': 0,
 'bg': 197,
--
    0000   0x03 0x00 0x00 0x00 0x2c                   ....,
    decimal
              3    0    0    0   44
    datetime (2012-10-19T23:34:54)
    0000   0xb6 0xa2 0x37 0x13 0x0c                   ..7..
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 7 Prime 2012-10-19T23:35:23 head[5], body[0] op[0x03]
###### DECODED
```python
{'amount': 0.5, 'fixed': 0.5, 'type': 'fixed'}
```
    op hex (5)
    0000   0x03 0x00 0x05 0x00 0x05                   .....
    decimal
              3    0    5    0    5
    datetime (2012-10-19T23:35:23)
    0000   0x97 0xa3 0x17 0x13 0x0c                   .....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 8 ResultTotals 2012-08-19T13:12:51 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0xe4                   .....
    decimal
              7    0    0    4  228
    datetime (2012-08-19T13:12:51)
    0000   0xb3 0x0c 0x6d 0xb3 0x0c                   ..m..
    body (41)
    hex
    0000   0x05 0x00 0xa5 0x4b 0xde 0x03 0x00 0x00    ...K....
    0008   0x04 0xe4 0x03 0x74 0x47 0x01 0x70 0x1d    ...tG.p.
    0010   0x00 0x66 0x01 0x70 0x1d 0x01 0x1c 0x4d    .f.p...M
    0018   0x00 0x54 0x17 0x00 0x00 0x00 0x03 0x02    .T......
    0020   0x00 0x01 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5    0  165   75  222    3    0    0
              4  228    3  116   71    1  112   29
              0  102    1  112   29    1   28   77
              0   84   23    0    0    0    3    2
              0    1    0   12    0  232    0    0
              0
    DAY BITS: [1, 0, 1]
#### RECORD 9 PumpSuspend 2012-10-20T09:45:58 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x00                                  ..
    decimal
             30    0
    datetime (2012-10-20T09:45:58)
    0000   0xba 0xad 0x09 0x14 0x0c                   .....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 10 PumpResume 2012-10-20T11:41:24 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x00                                  ..
    decimal
             31    0
    datetime (2012-10-20T11:41:24)
--
    0000   0x5c 0x05 0xfc 0x89 0x04                   \....
    decimal
             92    5  252  137    4
    datetime (unknown)

    body (0)

#### RECORD 20 Bolus 2012-10-20T23:41:53 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.0, 'dual_component': '??', 'programmed': 2.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x14 0x14 0x00                        ....
    decimal
              1   20   20    0
    datetime (2012-10-20T23:41:53)
    0000   0xb5 0xa9 0x57 0x14 0x0c                   ..W..
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 21 ResultTotals 2012-08-20T13:12:52 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0x7a                   ....z
    decimal
              7    0    0    4  122
    datetime (2012-08-20T13:12:52)
    0000   0xb4 0x0c 0x6d 0xb4 0x0c                   ..m..
    body (41)
    hex
    0000   0x05 0x00 0xb6 0x65 0xda 0x05 0x00 0x00    ...e....
    0008   0x04 0x7a 0x03 0x2e 0x47 0x01 0x4c 0x1d    .z..G.L.
    0010   0x00 0x5f 0x01 0x4c 0x1d 0x01 0x24 0x58    ._.L..$X
    0018   0x00 0x28 0x0c 0x00 0x00 0x00 0x02 0x01    .(......
    0020   0x00 0x01 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5    0  182  101  218    5    0    0
              4  122    3   46   71    1   76   29
              0   95    1   76   29    1   36   88
              0   40   12    0    0    0    2    1
              0    1    0   12    0  232    0    0
              0
    DAY BITS: [1, 0, 1]
#### RECORD 22 CalBGForPH 2012-10-21T02:04:12 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 202}
```
    op hex (2)
    0000   0x0a 0xca                                  ..
    decimal
             10  202
    datetime (2012-10-21T02:04:12)
    0000   0x8c 0x84 0x22 0x15 0x0c                   .."..
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 23 BolusWizard 2012-10-21T02:04:16 head[2], body[13] op[0x5b]
###### DECODED
```python
{'_byte[5]': 17,
--
    0000   0x01 0x1a 0x1a 0x00                        ....
    decimal
              1   26   26    0
    datetime (2012-10-21T21:20:54)
    0000   0xb6 0x94 0x95 0x15 0x0c                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 48 Bolus 2012-10-21T21:22:39 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.0, 'dual_component': '??', 'programmed': 2.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x14 0x14 0x02                        ....
    decimal
              1   20   20    2
    datetime (2012-10-21T21:22:39)
    0000   0xa7 0x96 0xb5 0x15 0x0c                   .....
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 49 ResultTotals 2012-08-21T13:12:53 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0xf8                   .....
    decimal
              7    0    0    4  248
    datetime (2012-08-21T13:12:53)
    0000   0xb5 0x0c 0x6d 0xb5 0x0c                   ..m..
    body (41)
    hex
    0000   0x05 0x00 0x92 0x65 0xce 0x06 0x00 0x00    ...e....
    0008   0x04 0xf8 0x03 0x7c 0x46 0x01 0x7c 0x1e    ...|F.|.
    0010   0x00 0x56 0x01 0x7c 0x1e 0x01 0x00 0x43    .V.|...C
    0018   0x00 0x7c 0x21 0x00 0x00 0x00 0x05 0x02    .|!.....
    0020   0x03 0x00 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5    0  146  101  206    6    0    0
              4  248    3  124   70    1  124   30
              0   86    1  124   30    1    0   67
              0  124   33    0    0    0    5    2
              3    0    0   12    0  232    0    0
              0
    DAY BITS: [1, 0, 1]
#### RECORD 50 CalBGForPH 2012-10-22T00:17:12 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 105}
```
    op hex (2)
    0000   0x0a 0x69                                  .i
    decimal
             10  105
    datetime (2012-10-22T00:17:12)
    0000   0x8c 0x91 0x20 0x16 0x0c                   .. ..
    body (0)
    HOUR BITS: [1, 0, 0]
#### RECORD 51 PumpSuspend 2012-10-22T19:07:18 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x00                                  ..
--
    0000   0x5c 0x08 0x08 0x0f 0x04 0x2c 0x19 0x04    \....,..
    decimal
             92    8    8   15    4   44   25    4
    datetime (unknown)

    body (0)

#### RECORD 60 Bolus 2012-10-22T20:39:26 head[4], body[0] op[0x01]
###### DECODED
```python
{'amount': 2.0, 'dual_component': '??', 'programmed': 2.0, 'type': '??'}
```
    op hex (4)
    0000   0x01 0x14 0x14 0x00                        ....
    decimal
              1   20   20    0
    datetime (2012-10-22T20:39:26)
    0000   0x9a 0xa7 0x54 0x16 0x0c                   ..T..
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 61 ResultTotals 2012-08-22T13:12:54 head[5], body[41] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0x00                   .....
    decimal
              7    0    0    4    0
    datetime (2012-08-22T13:12:54)
    0000   0xb6 0x0c 0x6d 0xb6 0x0c                   ..m..
    body (41)
    hex
    0000   0x05 0x00 0x8e 0x69 0xa1 0x04 0x00 0x00    ...i....
    0008   0x04 0x00 0x03 0x7c 0x57 0x00 0x84 0x0d    ...|W...
    0010   0x00 0x26 0x00 0x84 0x0d 0x00 0x70 0x55    .&....pU
    0018   0x00 0x14 0x0f 0x00 0x00 0x00 0x02 0x01    ........
    0020   0x00 0x01 0x00 0x0c 0x00 0xe8 0x00 0x00    ........
    0028   0x00                                       .
    decimal
              5    0  142  105  161    4    0    0
              4    0    3  124   87    0  132   13
              0   38    0  132   13    0  112   85
              0   20   15    0    0    0    2    1
              0    1    0   12    0  232    0    0
              0
    DAY BITS: [1, 0, 1]
#### RECORD 62 PumpSuspend 2012-10-23T08:41:47 head[2], body[0] op[0x1e]

    op hex (2)
    0000   0x1e 0x00                                  ..
    decimal
             30    0
    datetime (2012-10-23T08:41:47)
    0000   0xaf 0xa9 0x08 0x17 0x0c                   .....
    body (0)
    HOUR BITS: [1, 0, 1]
#### RECORD 63 PumpResume 2012-10-23T08:47:36 head[2], body[0] op[0x1f]

    op hex (2)
    0000   0x1f 0x00                                  ..
    decimal
             31    0
    datetime (2012-10-23T08:47:36)
--
              0    0    0    9  125
    HOUR BITS: [1, 0, 0]
#### RECORD 84 UnabsorbedInsulinBolus unknown head[14], body[0] op[0x5c]
###### DECODED
```python
[{'age': 9, 'amount': 1.8, 'curve': 4},
 {'age': 239, 'amount': 1.8, 'curve': 4},
 {'age': 173, 'amount': 2.85, 'curve': 20},
 {'age': 183, 'amount': 1.55, 'curve': 20}]
```
    op hex (14)
    0000   0x5c 0x0e 0x48 0x09 0x04 0x48 0xef 0x04    \.H..H..
    0008   0x72 0xad 0x14 0x3e 0xb7 0x14              r..>..
    decimal
             92   14   72    9    4   72  239    4
            114  173   20   62  183   20
    datetime (unknown)

    body (0)

`end logs/ReadHistoryData-page-26.data: 85 records`
