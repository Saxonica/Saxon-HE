==============================

Release notes for Saxon 11, dated 2022-07-28

Saxon 11.4 is the latest maintenance release on the Saxon 11 branch. Version numbers (except for
private builds) are now two-part numbers: X.Y where X is the major release and Y is the minor
(maintenance) release. Saxon 11.3 is released in three language versions: SaxonJ (Java), SaxonCS
(.NET 5+), and SaxonC (C/C++, PHP, and Python). For SaxonJ and SaxonC, there are three editions:
(EE, PE, and HE); for SaxonCS, only the enterprise edition (EE) is available.


The first release in the Saxon 11 series was SaxonCS-11.0, issued for the .NET 5 platform only on
2021-10-05. Saxon 11.1 (released 2022-02-01) provides a maintenance release for SaxonCS, and a first
release for SaxonJ and SaxonC. Saxon 11.3 (released 2022-03-28) provides a maintenance release for
SaxonJ, SaxonCS, and SaxonC; fixing a number of bugs and usability issues relative to 11.2. Saxon
11.4 (released 2022-07-28) provides a maintenance release for SaxonJ, SaxonCS, and SaxonC; with this
release, we are now recommending Saxon 11 as the most stable and reliable release for production use.

SaxonCS 11 requires .NET Core 5+; applications running on .NET Framework 4.x should stick with the
older product Saxon/.NET 10.x.

The documentation at http://www.saxonica.com/documentation/ includes a detailed list of changes for
each major release, and also includes installation instructions.

Links to all download files can be found at http://www.saxonica.com/download/download_page.xml

The file saxon-resources-11.zip contains documentation, sample files, test drivers and other
miscellaneous resources. It is common to all platforms, and is not normally updated when new
maintenance releases appear.

Most users will not need access to source code. For those that do, it is available in two forms.

(a) the raw source (with latest patches) is in a Git repository at
https://saxonica.plan.io/projects/saxonmirrorhe/repository.

(b) For convenience, the file saxon11-3source.zip on SourceForge contains preprocessed source code
that can be loaded directly into an IDE.

For a full list of bugs cleared in Saxon 11.4, please go to
https://saxonica.plan.io/projects/saxon/issues and filter the list of bugs for those labelled as
"Fixed in Maintenance Release 11.4"; or use this link
https://saxonica.plan.io/projects/saxon/issues?utf8=%E2%9C%93&set_filter=1&sort=id%3Adesc&f%5B%5D=status_id&op%5Bstatus_id%5D=c&f%5B%5D=cf_6&op%5Bcf_6%5D=%3D&v%5Bcf_6%5D%5B%5D=85&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=&t%5B%5D=

For further details of these bugs, or for details of bugs cleared in earlier maintenance releases,
or to register new bugs, please visit https://saxonica.plan.io/

