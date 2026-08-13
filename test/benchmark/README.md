# Benchmark Results

Performance comparison between govalid and popular Go validation libraries.

## Latest Results

**Benchmarked on:** 2026-08-13  
**Platform:** Linux 6.17.0-1020-azure x86_64  
**Go version:** go1.25.6

## Raw Benchmark Data

```
BenchmarkGoValidAlpha-4                    	79356009	        15.01 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundAlpha-4               	 2886948	       403.5 ns/op	       0 B/op	       0 allocs/op
BenchmarkAsaskevichGovalidatorAlpha-4      	11633076	       104.6 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateAlpha-4             	   68448	     17754 ns/op	   16815 B/op	      97 allocs/op
BenchmarkGoValidCELConcurrent-4            	266514265	         4.804 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELMultipleExpressions-4   	100000000	        11.97 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELBasic-4                 	100000000	        11.96 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELCrossField-4            	143336150	         8.398 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELStringLength-4          	1000000000	         1.000 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELNumericComparison-4     	1000000000	         1.057 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidEmail-4                    	19588371	        61.41 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundEmail-4               	 1208949	       989.7 ns/op	      88 B/op	       5 allocs/op
BenchmarkGoValidatorEmail-4                	 1320447	       908.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateEmail-4             	   83809	     14328 ns/op	   15708 B/op	      74 allocs/op
BenchmarkGoValidEnum-4                     	96810075	        12.49 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidGT-4                       	207763095	         5.883 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundGT-4                  	11720828	       102.5 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorGT-4                   	14244556	        88.07 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidGTE-4                      	200489318	         5.987 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundGTE-4                 	11960149	       100.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidIPV4-4                     	29731963	        40.24 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundIPV4-4                	10506427	       114.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidIPV6-4                     	12837822	       104.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundIPV6-4                	 7532913	       175.6 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidLength-4                   	124978363	         9.600 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLength-4              	12216976	        98.72 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorLength-4               	 5550026	       215.9 ns/op	      32 B/op	       2 allocs/op
BenchmarkGookitValidateLength-4            	   89455	     13369 ns/op	   15600 B/op	      78 allocs/op
BenchmarkGoValidLT-4                       	213088035	         5.630 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLT-4                  	11592112	       102.9 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidLTE-4                      	200356665	         5.987 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLTE-4                 	11777966	       101.6 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMaxItems-4                 	99831142	        12.10 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMaxItems-4            	 9491132	       126.6 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMaxLength-4                	31763943	        37.82 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMaxLength-4           	 9297795	       129.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorMaxLength-4            	 5017568	       237.2 ns/op	      32 B/op	       2 allocs/op
BenchmarkGookitValidateMaxLength-4         	   88670	     13372 ns/op	   15632 B/op	      80 allocs/op
BenchmarkGoValidMinItems-4                 	94570375	        12.67 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMinItems-4            	 9350337	       128.1 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMinLength-4                	57296025	        20.96 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMinLength-4           	10231496	       119.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorMinLength-4            	 4785270	       250.6 ns/op	      32 B/op	       2 allocs/op
BenchmarkGoValidNumeric-4                  	100000000	        11.33 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundNumeric-4             	15218620	        78.67 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorNumeric-4              	 9380806	       131.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateNumeric-4           	   86116	     13852 ns/op	   15533 B/op	      76 allocs/op
BenchmarkGoValidRequired-4                 	126240183	         9.506 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundRequired-4            	 9097833	       131.8 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorRequired-4             	567464007	         2.116 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateRequired-4          	   90613	     13033 ns/op	   15472 B/op	      72 allocs/op
BenchmarkGoValidURL-4                      	18097269	        64.04 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundURL-4                 	 2794435	       428.6 ns/op	     144 B/op	       1 allocs/op
BenchmarkGoValidatorURL-4                  	  109876	     10946 ns/op	     146 B/op	       1 allocs/op
BenchmarkGookitValidateURL-4               	   86715	     13929 ns/op	   15641 B/op	      75 allocs/op
BenchmarkGoValidUUID-4                     	18294739	        63.24 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundUUID-4                	 2784824	       421.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorUUID-4                 	 3667548	       329.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateUUID-4              	   84938	     14103 ns/op	   15501 B/op	      74 allocs/op
```

## Performance Comparison

| Validator | govalid | go-playground | vs go-playground | asaskevich/govalidator | vs asaskevich | gookit/validate | vs gookit |
|-----------|---------|---------------|------------------|----------------------|---------------|----------------|----------|
| LTE | 5.987 / 0 allocs | 101.6 / 0 allocs | **17.0x** | N/A | N/A | N/A | N/A |
| Enum | 12.49 / 0 allocs | N/A | N/A | N/A | N/A | N/A | N/A |
| Email | 61.41 / 0 allocs | 989.7 / 88 B / 5 allocs | **16.1x** | 908.4 / 0 allocs | **14.8x** | 14328 / 15708 B / 74 allocs | **233.3x** |
| GTE | 5.987 / 0 allocs | 100.4 / 0 allocs | **16.8x** | N/A | N/A | N/A | N/A |
| MinLength | 20.96 / 0 allocs | 119.2 / 0 allocs | **5.7x** | 250.6 / 32 B / 2 allocs | **12.0x** | N/A | N/A |
| UUID | 63.24 / 0 allocs | 421.4 / 0 allocs | **6.7x** | 329.7 / 0 allocs | **5.2x** | 14103 / 15501 B / 74 allocs | **223.0x** |
| MaxItems | 12.10 / 0 allocs | 126.6 / 0 allocs | **10.5x** | N/A | N/A | N/A | N/A |
| MaxLength | 37.82 / 0 allocs | 129.2 / 0 allocs | **3.4x** | 237.2 / 32 B / 2 allocs | **6.3x** | 13372 / 15632 B / 80 allocs | **353.6x** |
| LT | 5.630 / 0 allocs | 102.9 / 0 allocs | **18.3x** | N/A | N/A | N/A | N/A |
| MinItems | 12.67 / 0 allocs | 128.1 / 0 allocs | **10.1x** | N/A | N/A | N/A | N/A |
| Alpha | 15.01 / 0 allocs | 403.5 / 0 allocs | **26.9x** | 104.6 / 0 allocs | **7.0x** | 17754 / 16815 B / 97 allocs | **1182.8x** |
| Required | 9.506 / 0 allocs | 131.8 / 0 allocs | **13.9x** | 2.116 / 0 allocs | **0.2x** | 13033 / 15472 B / 72 allocs | **1371.0x** |
| IPV4 | 40.24 / 0 allocs | 114.2 / 0 allocs | **2.8x** | N/A | N/A | N/A | N/A |
| Length | 9.600 / 0 allocs | 98.72 / 0 allocs | **10.3x** | 215.9 / 32 B / 2 allocs | **22.5x** | 13369 / 15600 B / 78 allocs | **1392.6x** |
| IPV6 | 104.7 / 0 allocs | 175.6 / 0 allocs | **1.7x** | N/A | N/A | N/A | N/A |
| URL | 64.04 / 0 allocs | 428.6 / 144 B / 1 allocs | **6.7x** | 10946 / 146 B / 1 allocs | **170.9x** | 13929 / 15641 B / 75 allocs | **217.5x** |
| Numeric | 11.33 / 0 allocs | 78.67 / 0 allocs | **6.9x** | 131.4 / 0 allocs | **11.6x** | 13852 / 15533 B / 76 allocs | **1222.6x** |
| GT | 5.883 / 0 allocs | 102.5 / 0 allocs | **17.4x** | 88.07 / 0 allocs | **15.0x** | N/A | N/A |

## CEL Expression Validation (govalid Exclusive)

| CEL Validator | govalid (ns/op) | Allocations |
|---------------|-----------------|-------------|
| CELConcurrent | 4.804 | 0 allocs |
| CELMultipleExpressions | 11.97 | 0 allocs |
| CELBasic | 11.96 | 0 allocs |
| CELCrossField | 8.398 | 0 allocs |
| CELStringLength | 1.000 | 0 allocs |
| CELNumericComparison | 1.057 | 0 allocs |

CEL (Common Expression Language) support allows complex runtime expressions with near-zero overhead.

## Running Benchmarks

```bash
# Update all benchmark documentation
make sync-benchmarks

# Run benchmarks manually
cd test
go test ./benchmark/ -bench=. -benchmem -benchtime=10s

# Run specific validator benchmarks
go test ./benchmark/ -bench=BenchmarkGoValid{ValidatorName} -benchmem
```
