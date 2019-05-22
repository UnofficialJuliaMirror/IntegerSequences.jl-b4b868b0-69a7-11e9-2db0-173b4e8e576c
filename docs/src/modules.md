
   🔶  [Abundant](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/Abundant.jl)

``n`` is an abundant number if ``σ(n) > 2n``. An abundant number is a number for which the sum of its proper divisors is greater than the number itself.

isAbundant, is005101, I005101, F005101, L005101, V005101.

   🔶  [AndreNumbers](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/AndreNumbers.jl)

Generalized André numbers count the ``m``-alternating permutations of length ``n``, cf. A181937.

André, C000111, V000111, V178963, V178964, V181936, V250283.

```
[  SEQ  ] n|k [0][1][2][3][4] [5] [6]  [7]   [8]   [9]  [10]
[V000012] [1]  1, 1, 1, 1, 1,  1,  1,   1,    1,    1,     1
[V000111] [2]  1, 1, 1, 2, 5, 16, 61, 272, 1385, 7936, 50521
[V178963] [3]  1, 1, 1, 1, 3,  9, 19,  99,  477, 1513, 11259
[V178964] [4]  1, 1, 1, 1, 1,  4, 14,  34,   69,  496,  2896
[V181936] [5]  1, 1, 1, 1, 1,  1,  5,  20,   55,  125,   251
[V250283] [6]  1, 1, 1, 1, 1,  1,  1,   6,   27,   83,   209  
```

   🔶  [BellNumbers](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/BellNumbers.jl)

BellTrans, BellTriangle, BellNumberList, BellNumber, V000110, L000110, T137452, T264428, T137513, T104556, T001497, T132062, T039683, T203412, T004747, T051141, T265606, T119274, T000369, T051142

The Bell transform transforms an integer sequence into an integer triangle; also known as incomplete Bell polynomials.

Let ``X`` be an integer sequence, then ``B_{n,k}(X) = \\sum_{m=1}^{n-k+1} \\binom{n-1}{m-1} X[m] B_{n-m,k-1}(X)`` where ``B_{0,0} = 1, B_{n,0} = 0`` for ``n≥1, B_{0,k} = 0`` for ``k≥1``.

The Bell transform is (0,0)-based and the associated triangle always has as first column 1,0,0,0,... This column is often missing in the OEIS. Other Stirling number related sequences are implemented in the module StirlingLahNumbers.

   🔶  [BernoulliNumbers](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/BernoulliNumbers.jl)

BernoulliInt, BernoulliIntList, Bernoulli, BernoulliList, V195441, V065619, V281586, V281588, V027641, L065619

We are primarily concerned with the integer Bernoulli numbers. 
Cf. A000182 (m=2), A293951 (m=3), A273352 (m=4), A318258 (m=5).

[1] [0, 1,    0,       0,             0,                  0,                         0]
[2] [0, 1,   -2,      16,          -272,               7936,                   -353792]
[3] [0, 1,   -9,     477,        -74601,           25740261,              -16591655817]
[4] [0, 1,  -34,   11056,     -14873104,        56814228736,          -495812444583424]
[5] [0, 1, -125,  249250,   -2886735625,    122209131374375,     -14455143383196875000]
[6] [0, 1, -461, 5699149, -574688719793, 272692888959243481, -442144665466496478257141]

The rational Bernoulli numbers are defined here with B_(1) = 1/2. Why this is preferred over B_(1) = -1/2 is explained in  http://luschny.de/math/zeta/The-Bernoulli-Manifesto.html

   🔶  [BinaryInteger](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/BinaryInteger.jl)

V001855, V003314, V033156, V054248, V061168, V083652, V097383, V123753, V295513, BinaryIntegerLength, Bil

   🔶  [BinaryQF](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/BinaryQF.jl)

A binary quadratic form over Z is a quadratic homogeneous polynomial in two variables with integer coefficients, q(x, y) = ax^2 + bxy + cy^2. 

A quadratic form q(x, y) represents an integer n if there exist integers x and y with q(x, y) = n. We say that q primitively represents n if there exist relatively prime integers x and y such that q(x, y) = n.

Ported from [BinaryQuadraticForms](http://oeis.org/wiki/User:Peter_Luschny/BinaryQuadraticForms) where you can find much more information on this subject.

L002476, L008784, L031363, L034017, L035251, L038872, L038873, L042965, L057126, L057127, L068228, L084916, L089270, L141158, L242660, L243655, L244779, L244780, L244819, L243168, L244291, L007522, L033200

   🔶  [CantorMachines](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/CantorMachines.jl)

CantorMachine, CantorEnumeration, CantorPairing
CantorBoustrophedonicMachine, CantorBoustrophedonicEnumeration, CantorBoustrophedonicPairing
RosenbergStrongBoustrophedonicMachine, RosenbergStrongBoustrophedonicEnumeration, RosenbergStrongBoustrophedonicPairing

https://luschny.wordpress.com/2018/09/24/cantors-enumeration-of-n2-revisited/

   🔶  [CarmichaelNumbers](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/CarmichaelNumbers.jl)

isCarmichael, I002997, F002997, L002997

isweakCarmichael, I225498, F225498, L225498

   🔶  [ClausenNumbers](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/ClausenNumbers.jl)

ClausenNumber, ClausenNumberList
V002445, L002445, V027642

   🔶  [CombinationsIterator](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/CombinationsIterator.jl)

Combinations

   🔶  [Compositions](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/Compositions.jl)

I097805, L097805, V097805, M097805

   🔶  [Counts](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/Counts.jl)

L000961, L002808, L005117, L013928, L025528, L065515, L065855, L069637, L246547, L246655, L000720, A007917, A151800, A257993
PreviousPrime, NextPrime, PrimePiList, takeFirst, Nth, Count, List, HilbertHotel

   🔶  [CyclotomicBinaryForms](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/CyclotomicBinaryForms.jl)

Etienne Fouvry, Claude Levesque, Michel Waldschmidt, 
Representation of integers by cyclotomic binary forms
arXiv:1712.09019 [math.NT], 2017.

   🔶  [DedekindEta](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/DedekindEta.jl)

DedekindEtaPowers, RamanujanTau, RamanujanTauList, PartitionNumberList

   🔶  [DelehamDelta](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/DelehamDelta.jl)

DeléhamΔ, T084938, T060693, T106566, T094665, T090238, T225478, T055883, T184962, T088969, T090981, T011117

Applying Deléham's Δ-operation often gives an additional first column or an 
additional main diagonal in the resulting triangle compared to what is listed in the OEIS.

   🔶  [EulerTransforms](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/EulerTransforms.jl)

V006171, L006171, V107895, L107895, V061256, L061256, V190905, L190905, V275585, L275585, V290351, L290351

   🔶  [Fibonacci](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/Fibonacci.jl)

I000045, F000045, L000045, V000045, R000045, is000045

   🔶  [FigurativeNumbers](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/FigurativeNumbers.jl)

PolygonalNumber, PyramidalNumber
V014107, V095794, V067998, V080956, V001477, V000217, V000290
V000326, V000384, V000566, V000567, V001106, V001107
V005564, V058373, V254749, V000292, V000330, V002411, V002412
V002413, V002414, V007584, V007585

   🔶  [GaussFactorial](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/GaussFactorial.jl)

I193338, F193338, L193338, V193338, I193339, F193339, L193339, V193339

   🔶  [GeneralizedBinomial](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/GeneralizedBinomial.jl)

Binomial, Pascal, T007318

   🔶  [HighlyAbundant](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/HighlyAbundant.jl)

I002093, F002093, L002093, V002093
I034885, F034885, L034885, V034885

   🔶  [Hyper1F1](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/Hyper1F1.jl)

GammaHyp, V000255, V000262, V001339, V007060, V033815, V099022, V251568

   🔶  [JacobiTheta](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/JacobiTheta.jl)

JacobiTheta3Powers, JacobiTheta4Powers, L000122, L002448, L004018, L104794, L005875, L213384, L000118, L035016, L008452, L096727, L000132, L000141, L008451, L000143, L000144, L008453, L000145, L276285, L276286, L276287, L004402, L004406, L004407, L015128, L004403, L001934, L004404, L004405, L004408, L004409, L004410, L004411, L004412, L004413, L004414, L004420, L004421, L004415, L004416, L004417, L004418, L004419, L004422, L004423, L004424, L004425

The ``q``-expansion of the Jacobi theta functions 3 and 4 raised to the power ``r`` is computed for various values of ``r``.

   🔶  [Kolakoski](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/Kolakoski.jl)

KolakoskiList, C000002, I000002, L000002

   🔶  [NarayanaCows](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/NarayanaCows.jl)

NarayanasCows, L214551

For background information see 
http://recherche.ircam.fr/equipes/repmus/jim96/actes/Allouche.ps
https://iopscience.iop.org/article/10.1088/1742-6596/574/1/012097/pdf

   🔶  [NumberTheory](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/NumberTheory.jl)

τ, σ, σ2, ϕ, ω, Ω, ⊥, ⍊, Divisors, PrimeDivisors, Factors, Radical, mods
V000005, V000010, V000203, V001222, V001221, V008683, V181830, V034444
I003277, L003277, V061142, V034386, V002110, I050384, L050384, V001157
Divides, isPrime, isCyclic, isStrongCyclic, isOdd, PrimeList
isPrimeTo, isStrongPrimeTo, isNonnegative, isPositive, isEven, isSquare
isComposite, isSquareFree, isPrimePower, isPowerOfPrimes, isPerfectPower

   🔶  [OEISUtils](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/OEISUtils.jl)

Returns the path where the oeis data is expected.

   🔶  [OrthoPolynomials](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/OrthoPolynomials.jl)

OrthoPoly, InvOrthoPoly
T053121, T216916, T217537, T064189, T202327, T111062, T099174, T066325, T049310, T137338, T104562, T037027, T049218, T159834, T137286
T053120, T053117, T111593, T059419, L217924, L005773, L108624, L005425, L000085, L001464, L003723, L006229

   🔶  [Partitions](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/Partitions.jl)

Partition, V080577

An alternative to Combinatorics.partitions(n).

For n = 100 the benchmark shows:

* 167.598273 seconds (15 allocations: 4.813 KiB)

*  86.960344 seconds (381.14 M allocations:  48.735 GiB, 11.29% gc time)

Our function takes twice as long but the Combinatorics's function takes vastly more space.

   🔶  [PrimesIterator](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/PrimesIterator.jl)

Primes, PrimePi, PrimeSieve

   🔶  [PrimeSwingFactorial](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/PrimeSwingFactorial.jl)

PSfactorial, Swing

   🔶  [Products](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/Products.jl)

∏, Product, F!, RisingFactorial, ↑, FallingFactorial, ↓, MultiFactorial
V000407, V124320, V265609, V000142, V081125, V001147
V000165, V032031, V007559, V008544, V007696, V001813, V008545, V047053

   🔶  [QueensProblems](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/QueensProblems.jl)

L319284, Queens

   🔶  [RationalTrees](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/RationalTrees.jl)

EuclidTree, CalkinWilfTree, SchinzelSierpinskiEncoding

Rational trees as understood here are binary trees enumerating the positive or 
nonnegative rational numbers. Examples are the Euclid tree, the Kepler tree and the
Stern-Brocot tree (a.k.a. Farey tree). They are closely related to binary partitions
and to Stern's diatomic sequence or Dijkstra's fusc function.

See Malter, Schleicher, Zagier, New looks at old number theory, Amer. Math. Monthly, 120(3), 2013, pp. 243-264.

   🔶  [RecordSearch](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/RecordSearch.jl)

The type object to construct an iterated search for records in sequences.

Records

   🔶  [RiordanSquares](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/RiordanSquares.jl)

RiordanProduct, RiordanSquare
T039599, T116392, T172094, T321620, T321621
T321623, T321624, T322942

   🔶  [SelfConvolutive](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/SelfConvolutive.jl)

SelfConvRec
L000698, L001710, L003319, L005411, L005412, L006012, L006318
L047891, L062980, L082298, L082301, L082302, L105523, L107716
L111529, L111530, L111531, L111532, L111533, L146559, L167872

   🔶  [SeqUtils](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/SeqUtils.jl)

Think of a 'Nemo.fmpz' as a 'BigInt'. 'fmpz' stands for 'fast multiple precision zahl (Zahl=integer)'. Nemo is a library designed, developed and maintained by William Hart with the help of others. The mathematical symbol for the ring of
integers is the blackbord (double-struck) Z, also written ZZ. In reference to this ZZ(n) defines the integer n as a fmpz.

   🔶  [SeriesExpansion](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/SeriesExpansion.jl)

Coefficients, G000045, G000257, L000257
G000032, L000032, G000073, L000073, G000108, L000108, G000957, L000957
G001003, L001003, G001006, L001006, G001045, L001045, G002426, L002426
G005043, L005043, G006318, G068875, L068875

   🔶  [StirlingLahNumbers](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/StirlingLahNumbers.jl)

I132393, L132393, V132393, M132393
I048993, L048993, V048993, M048993
I271703, L271703, V271703, M271703
I094587, L094587, V094587, M094587
I008279, L008279, V008279, M008279

   🔶  [SwingFactorial](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/SwingFactorial.jl)

Sfactorial

Basic implementation of the swing algorithm using no primes. 
Claims to be the most efficient simple algorithm to compute the factorial.

An advanced version based on prime-factorization is available 
as the prime-swing factorial factorialPS.

   🔶  [Triangles](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/Triangles.jl)

Triangle, ZTriangle, QTriangle, RecTriangle, TriangularNumber, isTriangular, assertTriangular
ShowAsΔ, ShowAsMatrix, Row, RowSums, fromΔ, toΔ, TriangleToList

   🔶  [UlamNumbers](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/UlamNumbers.jl)

L002858, UlamList, isUlam

   🔶  [ZumkellerNumbers](https://github.com/OpenLibMathSeq/IntegerSequences.jl/blob/master/src/ZumkellerNumbers.jl)

isZumkeller, is083207, I083207, F083207, L083207, V083207