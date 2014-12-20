# DC Voter Registration Data

 * [20141218-dc_voters.csv.zip](20141218-dc_voters.csv.zip): zipped data file with header row and 469,610 rows of voter registration data
 * [20141218-dc_voters.txt](20141218-dc_voters.txt): the original provided documentation, received as `Read Me.txt`

On Thursday December 18 2014 I took a printed copy of a [PDF form](http://www.dcboee.org/pdf_files/Data_Request_Form.pdf) that I found on the [DC Board of Elections web site](http://www.dcboee.org/) to 441 4th Street NW, Suite 250 North, Washington, DC, 20001. I had to show ID, have my bag x-rayed, and go through a metal detector to get into the building. The security guards were nice.

I brought my checkbook so I could pay $2 for a CD-ROM of voter registration data. The clerk who helped me was very friendly. She informed me that the data is updated daily, but nobody comes in daily. She burned my CD while I waited. She told me there are no rules on how the data can be used. I take it to be public domain.

On the CD were two files:

The data file was a Microsoft Access database file: `DC VH EXPORT.MDB`, 154 megabytes. I bought a PC laptop running Windows 8, purchased and installed Microsoft Access, opened and exported the data as text. It comes to 130 megabytes as uncompressed text. I was able to get the column headers out and stick them on top of the file so that it can be read as CSV. Zipped using the Windows zip functionality the result is [20141218-dc_voters.csv.zip](20141218-dc_voters.csv.zip), at 20 megabytes.

The provided documentation file was plain text, `Read Me.txt`. I renamed this to [20141218-dc_voters.txt](20141218-dc_voters.txt). It seems slightly out of date with respect to the data in that the later columns corresponding to elections are not the same in the documentation and in the data. These column names are interpretable as MMYYYY-T, I believe, where MM is numeric month, YYYY is four-digit year, and T is a letter corresponding to election type. I think G is General and P is primary.
