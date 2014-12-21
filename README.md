# DC Voter Registration Data

 * [20141218-dc_voters.csv.zip](20141218-dc_voters.csv.zip): zipped data file with header row and 469,610 rows of data
 * [20141218-dc_voters.txt](20141218-dc_voters.txt): original documentation, received as `Read Me.txt`

On Thursday, December 18, 2014, I took a printed copy of a [PDF form](http://www.dcboee.org/pdf_files/Data_Request_Form.pdf) that I found on the [DC Board of Elections web site](http://www.dcboee.org/) to 441 4th Street NW, suite 250 north, Washington, DC, 20001. I had to show ID, have my bag x-rayed, and go through a metal detector to get into the building.

I brought my checkbook so I could pay $2 for a CD-ROM of voter registration data. The clerk informed me that the data is updated daily. She burned my CD while I waited. She told me there are no rules on how the data can be used. I take it to be public domain.

On the CD were two files:

 * The data was in a Microsoft Access database file called `DC VH EXPORT.MDB` (154 MB). I bought a PC laptop running Windows 8, purchased and installed Microsoft Access, opened the file and exported the data as text. It comes out as 130 megabytes of uncompressed text. I was able to get the column headers out and stick them on top of the file so that it can be read as nice CSV. Zipped (using the Windows built-in) the result is the 20 MB [20141218-dc_voters.csv.zip](20141218-dc_voters.csv.zip).
 * The provided documentation file was a plain text `Read Me.txt`. I renamed this to [20141218-dc_voters.txt](20141218-dc_voters.txt). It seems slightly out of date with respect to the data in that the later columns corresponding to elections are not the same in the documentation and in the data. These column names are interpretable as MMYYYY-T, I believe, where MM is numeric month, YYYY is four-digit year, and T is a letter corresponding to election type. I think G is General and P is primary.
