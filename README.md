6Lo Test Descriptions
=====================

This repository contains the Test Descriptions for the ETSI 6Lo plugtest in Yokohama, Japan, 2015-11-06..-08.

For now, this is described in a single area of testing, with a pair of files:

| Area     | source file                                                            | HTML version                                                        | PDF version                                                            |
| ---      | ---                                                                    | ---                                                                 |                                                                        |
| Base 6Lo | [6lo.yml](http://github.com/6lo/test-descriptions/blob/master/6lo.yml) | [6lo.html](http://rawgit.com/6lo/test-descriptions/master/6lo.html) | [6lo.pdf](https://github.com/6lo/test-descriptions/raw/master/6lo.pdf) |
|          |                                                                        |                                                                     |                                                                        |

The source file is intended as a machine-readable (but textual) form
of the test (still with English phrases, though); it is encoded in
YAML format.  The HTML file is a human-readable form suitable for
inclusion in the final plugtest guide document.  The PDF file shows
that HTML file, with no page breaks within a single test.

Not all tests apply to all 6Lo technologies.  Each of the tests is
marked with the specific technologies they are intended to be used
with (heading "Technologies").

Some tests are marked *basic*, some other tests are marked *advanced*.
Generally, all implementations should be able to handle the basic
tests for their technology.  There may be some obstacles to performing
the advanced tests.
