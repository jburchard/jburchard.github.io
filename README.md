## About

This is a gallery of random projects I have or am in the process of developing. A few things things that you should know about this:

- Most of them are tools built to support progressive politics and organizations. Therefore, it is unlikely that I will make the code base public as I have strong opinons as to who should have access to these tools.* However, if you are of like mind and wish to collaborate, please do feel free to reach out.

- Most of them are works in progress and should be considered toy apps. They most likely have little test coverage and are not production ready. They will probably all break if pushed.

###### **That is making the assumption, that these tools are actually useful in winning campaigns, which is up for debate.*

### GOTV Tracker
This is a tool which seeks to solve for the constant challenge of tracking turf during GOTV. The best solutions that I've seen for this have been a series of linked GoogleDocs, with a bunch of protected cells and pivot tables. This is a great solution in that it relies on Google to keep the servers going if and when they inevitably get hammered by tons of viewers. However, it is still hard to maintain and needs to a bunch of work each time GOTV rolls around.

The goal of the GOTV tracker is to solve for this. There are a few guiding goals behind this project:

- Simple and Intuitive Data Entry: It should be completely intuitive for anyone to update the status of packets and the should be unable to break the tracker through an errant click. The goal is to keep the page uncluttered and allow for fast and error-free data entry.

- Flexible Hierarchy: Reporting structures come in all shapes and sizes and the tool should be flexible to allow for this. The tool will allow you to set easily set the hierarchy of reporting and turf, such as:

  - State HQ >> Regions >> Staging Location >> Precinct >> Turf
  - Organization >> Staging Locations >> Turf
  - HQ >> Staging Locations >> Canvasser Van >> Turf


- Simple Reporting: A simple dashboard that allows for reporting 

