# gst-python-tester
Python script for testing Gstreamer pipelines

First tester version
    
Features:
 - Will run two pipelines in each test
 - File with the pipelines to test, each test has an ID and the pattern
   to add more tests is:
 
		 ID:::PIPELINE1:::PIPELINE2:::GST_DEBUG_LEVEL

 - Will run all the tests continuously
 - Will create a log summary for the tests suite
 - Will create a log for each pipeline depending on the DEBUG_LEVEL set