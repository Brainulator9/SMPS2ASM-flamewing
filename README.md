# SMPS2ASM
This is Brainulator9's version of Flamewing's version of SMPS2ASM, as originally made by Cinossu. Because SMPS2ASM has no native repository, I just decided to strip this down to only SMPS2ASM. The **backmerge** branch is meant to be used whenever I want to make changes for flamewing to adopt.

If you use this, just be sure to place this at the start of your sound engine code:
```
; Used by SMPS2ASM include file.
; Set the following based on which game this is:
; * 1 for Sonic 1
; * 2 for Sonic 2
; * 3 for Sonic 3
; * 4 for Sonic & Knuckles (and Sonic 3D?)
; * 5 for flamedriver
SonicDriverVer			= 5
; Set the following to non-zero to use all S2 DAC samples, or to zero otherwise.
; The S1 samples are a subset of this.
use_s2_samples			= 1
; Set the following to non-zero to use all S3D DAC samples, or to zero otherwise.
; Most of the S3D samples are also present in S3/S&K, but there are two samples specific to S3D.
use_s3d_samples			= 1
; Set the following to non-zero to use all S3 DAC samples, or to zero otherwise.
use_s3_samples			= 1
; Set the following to non-zero to use all S&K DAC samples, or to zero otherwise.
use_sk_samples			= 1
```
