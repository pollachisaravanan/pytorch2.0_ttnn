### aten.tanh.default
|    | ATen Input Variations          | Status   | Isolated   | PCC                | Host   |
|---:|:-------------------------------|:---------|:-----------|:-------------------|:-------|
|  0 | Tensor<[1, 1, 1024]> self = ?  | Unknown  | Done       | 0.9999435913997913 | 0      |
|  1 | Tensor<[1, 1, 24576]> self = ? | Unknown  | Unknown    | N/A                | N/A    |
|  2 | Tensor<[1, 1, 3072]> self = ?  | Unknown  | Done       | 0.9999418091208283 | 0      |
|  3 | Tensor<[1, 1, 4096]> self = ?  | Unknown  | Done       | 0.9999402923387358 | 0      |
|  4 | Tensor<[1, 12, 3072]> self = ? | Done     | Done       | 0.9999420639035858 | 0      |
|  5 | Tensor<[1, 14, 3072]> self = ? | Done     | Done       | 0.9999423671223753 | 0      |
|  6 | Tensor<[1, 15, 1024]> self = ? | Unknown  | Done       | 0.9999416316354436 | 0      |
|  7 | Tensor<[1, 256, 96]> self = ?  | Unknown  | Unknown    | N/A                | N/A    |
|  8 | Tensor<[1, 32, 6144]> self = ? | Done     | Done       | 0.9999421580824449 | 0      |
|  9 | Tensor<[1, 45, 3072]> self = ? | Unknown  | Done       | 0.9999416124360874 | 0      |
| 10 | Tensor<[1, 5, 4096]> self = ?  | Unknown  | Done       | 0.9999417162343728 | 0      |
| 11 | Tensor<[1, 7, 3072]> self = ?  | Done     | Done       | 0.9999422134560486 | 0      |
| 12 | Tensor<[1, 768]> self = ?      | Done     | Done       | 0.9999431951288816 | 0      |
| 13 | Tensor<[1, 9, 128]> self = ?   | Done     | Done       | 0.9999435650854993 | 0      |
| 14 | Tensor<[1, 9, 16384]> self = ? | Done     | Done       | 0.9999421454185847 | 0      |
| 15 | Tensor<[1, 9, 3072]> self = ?  | Done     | Done       | 0.999942147866077  | 0      |
| 16 | Tensor<[1, 9, 4096]> self = ?  | Done     | Done       | 0.9999416286601474 | 0      |
| 17 | Tensor<[1, 9, 8192]> self = ?  | Done     | Done       | 0.9999412952288655 | 0      |

