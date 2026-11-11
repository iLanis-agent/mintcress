# Mintcress 1.0 TEST
Native Android minimum-coin exact-change puzzle. Android8+ min26/target35. Package com.gg007.mintcress.

## Rules
Make the printed target exactly using six coin values with unlimited supply. Tap plus or minus to add or remove one coin of that row. Minimize the total number of coins, not their values. Adding beyond the target and removing below zero are blocked. Press CHECK CHANGE explicitly. Twelve original denomination-target pairs, one optimal count-vector each. Every board defeats largest-first greedy. Coin values are abstract puzzle units, not real currency. Undo/reset and saved palette/optional count multipliers.

## Download and status
https://mega.co.nz/#!8Ns0mJ5J!9qmuriMiIzL8CVQQL7oQKWcSmVox-ftWQOvflCgILBE
APK16878bytes; SHA2565e5e8b48b27b2e6dd024581ecf29c3669265aaf4b9f03d51479fdf9db1200fb5. Original certificate SHA2561651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions. GG007 icon unchanged. Anonymous downloaded bytes exact.

## Checks
Independent recursive count-vector enumeration checks 46789 feasible selections across twelve boards against production one-dimensional minimum-coin dynamic programming. Every board has one minimum count-vector and a worse largest-first greedy result. Another 1000 random instances and 72 plus/undo/reset cases pass, plus target cap, zero target, single coin, unreachable target, tied optima, negative count and bounds cases. Twelve actual plus/CHECK optimum tap-solves and greedy/early-check rejection, minus/undo/reset, solved locks, NEXT, levels/menu/privacy and saved palette/multipliers pass. Twenty drawing previews visually inspected, not phone screenshots. Original signing certificate/icon unchanged, no permissions. Anonymous APK bytes match. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Current 240 studio descriptions and 803 legacy descriptions reviewed. Weightwake chooses tiles satisfying weighted row and column sums; Covercress selects finite bundles to cover a union; Assigncress uses each worker and job exactly once. Mintcress instead chooses nonnegative counts from unlimited denominations, reaches one exact target and minimizes the number of pieces. Legacy Coin Math concerns cash-machine fees, not change composition. No matching factory mechanic found. Known minimum-coin change-making adaptation, not a globally new algorithm. Original seeded noncanonical coin systems, native implementation and count-adjustment interaction.

## Build and tests
JDK17/AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/mint-test src/com/gg007/mintcress/Board.java BoardTest.java then java -cp /tmp/mint-test com.gg007.mintcress.BoardTest. bash build.sh produces an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private signing material. No signing secret included. adapter/android is the Java2D drawing adapter used with MintAdapterTest.java, not an Android runtime.

## Privacy and branding
Mintcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, count-multiplier labels and solved-level marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon, studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK/exact cumulative241cardstudio/publishing fragments privately preserved:
https://files.instinct.com/j54xzf221m2o-mintcress-source-archive
https://github.com/iLanis-agent/mintcress holds README only; full Git source pending. All four studio includes and Pages settings unchanged. Both sites verified separately.

## Rule sources
https://www.math.umd.edu/~immortal/CMSC351/notes/coinchanging.pdf
https://www.cs.cmu.edu/~gauravar/notes/classes/class4.pdf
https://www.cs.ox.ac.uk/files/12572/dynamic.pdf
https://webpages.charlotte.edu/rbunescu/courses/ou/cs4040/lecture19.pdf
https://www.cs.umb.edu/~nurith/cs612/dynamicProgramming_notes.pdf
https://en.wikipedia.org/wiki/Change-making_problem
