# TestDump

A couple of notes,

If we want to record changes to keep all of the meta information in sync, we would need to clear the sha each time so that the next time we sync, 
it updates the meta file

there may be a few issues if a new category is added on a remote and we blindly suck in the records without updating the sequence. I think this is
the only table that would have this issue. 

I have retained the meta fields as we may want to update things like what libraries go with which wf specs, changes to category names, displaynames on workflow 
specs, etc. 
