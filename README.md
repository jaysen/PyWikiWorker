
PyWikiWorker (was going to be WikiThing)
===============================

Python tools for working with wikis. Initially will focus on standalone text based wikis - and have an interface implemented for WikidPad.

##Initial Goals

Simple text based appending to wikipages, creating the WikiPage if necessary.
Will be invoked by AlfredScript and CommandLine and store in a flat-file local wiki, like WikidPad

##Initial Features:
 
  * WikiWorkerClass
  
    * FindWiki (wiki_name)
    * OpenWiki (folder_path)
    * CopyWiki (folder_path_src, folder_path_dest)
    * GetPages (Tag_Set OR Category_Set) -- ie. by TagCombinations or CategoryCombinations
 

 * WikiClass

	 * SetDataFolder
	 * GetWikiPage (wikipage_name)
	 * CreateWikiPage (wikipage_name)
	 * GetWikiPageAsString()
	 * SetWikiPageFromString(new_page_as_string)
	 * GetPages (Tag_Set)
	 * GetPages (Category_Set)
	 * CreateWikiPageTemplate
	 * UseWikiPageTemplate
 
##Potential Features / Down the line
Has potential to grow to a set of tools + library + GUI tools for doing Wiki related tasks, and for advanced mining, browsing and searching of a wiki.
