## Patent extraction, exploratory data analysis and modeling applications

Patent numbers are loaded from the US Patent and Trademark Office (www.uspto.gov) and formatted to run in the extraction program.  The extraction program downloads data from Google patent webpags.  Data from patent extraction is then plotted using exploratory data analysis or examined by natural language processing.  In some cases, the data is loaded into regression pipelines for further analysis, for instance, to predict the number of forward citations based on data within the patent.  

df_patents = patent dataframe 

	num_rb       = number of forward citations
	num_inventor = number of inventors 
	num_pc       = number of reverse patent citations 
	num_npc      = number of non-patent citations 
	num_class    = number of classifications 
	num_le       = number of legal events 

Other features of patents that are extracted: 

	titles       = patent title 
	issue_date   = date patent issued (yyyy-mm-dd) 
	
 
