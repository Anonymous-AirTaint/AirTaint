# Minor Notes

## Reviewer A

- “AirTaint” means our wish to perform taint analysis as easily as breathing air.
- We will give a clearer description of the pre-processing of call instructions in Section 3.1.1 in the revision.
- Because libdft depends on Pin 2.14, which requires an old version of Linux Kernel (i.e., less than 4.x.x), AirTaint chooses a proper version (i.e., 14.04.6) of Ubuntu in our experiment.
- Because TinTin++ and exim are client and server programs. Once the input has been executed, the program will continue to wait for a new input. If we want to record the executed instruction trace, we have to insert the terminate code at the right place to make the program exit. So we temporarily exclude these two programs in Section 5.2.2.

## Reviewer B

- We will add a relevant description to illustrate Figure 2 in the revision.
- We will define “Context switch” before using it and analyze the extent of its impact on performance in the revision.
