# Pacing Guide

To use the sample file in your code, download the file and run the following code to obtain a sample list of events:

    import json
    with open('events_list_sample.json', 'r')) as f:
      events_list = json.loads(f.read())
