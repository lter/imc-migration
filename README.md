# imc-migration
This repo contain the migration classes to move the content and structure from the US-LTER Information Managers site to a supported Drupal platform

Drupal Content types, views and vocabularies are featurized.

Menus recreated.

Theme converted to responsive/adaptive (Pix Reloaded)

Vocabularies, nodes are migrated -- a collection of assets will follow.


|Item Name|# nodes|Migration Plan|Deprecated Notes|
|---|---|---|---|
|Abstract 2010|	10|||
|Abstract 2011|	0	|deprecate|	Zero nodes|
|Blog entry|0	|deprecate	|Zero nodes|
|Book page|	100+|||		
|Event	|44		|||
|Forum topic|	14	|||	
|Image	|42	||to img type|	
|Issue|28|||		
|Page	|100+||		
|Poll	|0	|deprecate|	Zero nodes|
|Project	47		|||
|Project release|	40	|||
|Story|100+		|||
|Timeline Event|7|||		
|Webform||||			
|weblink|	4	|deprecate||	

Here is a list of vocabularies, their terms, and suggested actions.


|Vocabulary Name|Used By	Module-content type| Vid|	# terms|	Plan / Notes|
|---|---|---|---|---|
|Forums	|Forum topic	|	3	|2	||
|Help	||6	|3	||
|IM Categories|Book page, Project	|7|100+||
|Links||4|21||
|Project release API compatibility|	Project, Project release	|2|1|deprecate|
|Project types		||1	|0|	deprecate|
|Working Groups	|Project, Story	|	5|32||
|LTER Sites|	Book page	|	8	|26||
