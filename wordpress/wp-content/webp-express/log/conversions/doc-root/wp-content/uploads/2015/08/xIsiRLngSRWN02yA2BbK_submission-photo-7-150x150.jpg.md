WebP Express 0.15.3. Conversion triggered using bulk conversion, 2019-09-24 05:02:46

*WebP Convert 2.1.4*  ignited.
- PHP version: 7.3.1
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg.webp
- log-call-arguments: true
- converters: (array of 9 items)

The following options have not been explicitly set, so using the following defaults:
- converter-options: (empty array)
- shuffle: false
- preferred-converters: (empty array)
- extra-converters: (empty array)

The following options were supplied and are passed on to the converters in the stack:
- default-quality: 70
- encoding: "auto"
- max-quality: 80
- metadata: "none"
- near-lossless: 60
- quality: "auto"
------------


*Trying: cwebp* 

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg
- destination: [doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg.webp
- default-quality: 70
- encoding: "auto"
- low-memory: true
- log-call-arguments: true
- max-quality: 80
- metadata: "none"
- method: 6
- near-lossless: 60
- quality: "auto"
- use-nice: true
- command-line-options: ""
- try-common-system-paths: true
- try-supplied-binary-for-os: true

The following options have not been explicitly set, so using the following defaults:
- alpha-quality: 85
- auto-filter: false
- preset: "none"
- size-in-percentage: null (not set)
- skip: false
- rel-path-to-precompiled-binaries: *****
------------

Encoding is set to auto - converting to both lossless and lossy and selecting the smallest file

Converting to lossy
Locating cwebp binaries
1 cwebp binaries found in common system locations
Checking if we have a supplied binary for OS: Darwin... We do.
We in fact have 1
A total of 2 cwebp binaries where found
Detecting versions of the cwebp binaries found (and verifying that they can be executed in the process)
Executing: /usr/local/bin/cwebp -version. Result: version: 1.0.3
Executing: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12 -version
Exec failed (the cwebp binary was not found at path: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12)
Trying executing the cwebs found until success. Starting with the ones with highest version number.
Creating command line options for version: 1.0.3
Quality of source is 82. This is higher than max-quality, so using max-quality instead (80)
The near-lossless option ignored for lossy
Trying to convert by executing the following command:
nice /usr/local/bin/cwebp -metadata none -q 80 -alpha_q '85' -m 6 -low_memory '[doc-root]/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg.webp.lossy.webp' 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg.webp.lossy.webp'
File:      [doc-root]/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg
Dimension: 150 x 150
Output:    4418 bytes Y-U-V-All-PSNR 40.47 43.76 43.36   41.27 dB
           (1.57 bpp)
block count:  intra4:         94  (94.00%)
              intra16:         6  (6.00%)
              skipped:         3  (3.00%)
bytes used:  header:             83  (1.9%)
             mode-partition:    495  (11.2%)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |    2958 |      13 |      23 |      22 |    3016  (68.3%)
 intra16-coeffs:  |      18 |       0 |      15 |       0 |      33  (0.7%)
  chroma coeffs:  |     739 |       3 |      12 |       6 |     760  (17.2%)
    macroblocks:  |      94%|       1%|       3%|       2%|     100
      quantizer:  |      20 |      14 |      11 |      11 |
   filter level:  |       7 |       3 |       2 |       0 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |    3715 |      16 |      50 |      28 |    3809  (86.2%)

Success
Reduction: 31% (went from 6429 bytes to 4418 bytes)

Converting to lossless
Locating cwebp binaries
1 cwebp binaries found in common system locations
Checking if we have a supplied binary for OS: Darwin... We do.
We in fact have 1
A total of 2 cwebp binaries where found
Detecting versions of the cwebp binaries found (and verifying that they can be executed in the process)
Executing: /usr/local/bin/cwebp -version. Result: version: 1.0.3
Executing: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12 -version
Exec failed (the cwebp binary was not found at path: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12)
Trying executing the cwebs found until success. Starting with the ones with highest version number.
Creating command line options for version: 1.0.3
Trying to convert by executing the following command:
nice /usr/local/bin/cwebp -metadata none -q 80 -alpha_q '85' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg' -o '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg.webp.lossless.webp' 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg.webp.lossless.webp'
File:      [doc-root]/wp-content/uploads/2015/08/xIsiRLngSRWN02yA2BbK_submission-photo-7-150x150.jpg
Dimension: 150 x 150
Output:    19014 bytes (6.76 bpp)
Lossless-ARGB compressed size: 19014 bytes
  * Header size: 1539 bytes, image data size: 17449
  * Lossless features used: PREDICTION CROSS-COLOR-TRANSFORM SUBTRACT-GREEN
  * Precision Bits: histogram=2 transform=2 cache=0

Success
Reduction: -196% (went from 6429 bytes to 19014 bytes)

Picking lossy
cwebp succeeded :)

Converted image in 200 ms, reducing file size with 31% (went from 6429 bytes to 4418 bytes)
