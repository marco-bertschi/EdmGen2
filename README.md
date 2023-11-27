# EdmGen2

## Notes

The code in this repository has been modified from the original repo located at [cincuranet/EdmGen2](https://github.com/cincuranet/EdmGen2).
Changes were made to port the tool onto .Net 4.8 and also remove some dependencies to 3rd party libraries.

## Raison d’Être

This Repo was forked from [cincuranet/EdmGen2](https://github.com/cincuranet/EdmGen2) for a simple reason: The EF 6 Power Tools are not to be used with VS 2022.
Some parties may not be able to upgrade to EF Core as fast as they would like, therefore they are stuck with EF 6 and yet have to advance onto VS 2022.
In order to be able to still pregenerate tools with EF 6 and VS 2022, this little command line utility comes in handy. It's not a replacement for the EF 6 Power Tools in
VS 2022, but only a tool which allows the developer to stick with EF 6 for a little longer. That said, you should aim to upgrade to EF Core as soon as you can, and use this tool
only to leverage some of the symptoms you may experience until you can upgrade.

## Change Log

* Nov. 27nd 2023
  * Port to .Net 4.8
  * Remove dependency to ConceptualEdmGen.dll - See [Where is the code for ConceptualEdmGen.dll?](https://github.com/cincuranet/EdmGen2/issues/6) for more information about this DLL.

## Resources

* [EdmGen2 sources moved](http://blog.cincura.net/233421-edmgen2-sources-moved/)
* [EdmGen2 for .NET 4.5 and Entity Framework 5](http://blog.cincura.net/233311-edmgen2-for-net-4-5-and-entity-framework-5/)
* [EdmGen2 with EFv4](http://blog.cincura.net/231221-edmgen2-with-efv4/)
* [Make your Entity Framework model faster (with EdmGen2)](http://blog.cincura.net/228787-make-your-entity-framework-model-faster-with-edmgen2/)
* [EdmGen on steroids? EdmGen2!](http://blog.cincura.net/227892-edmgen-on-steroids-edmgen2/)