**Table 1: FINANCIALS.MARVELL_DEMO.INVENTORY_ACTUALS (Stores Actual Inventory ITEM information for  Different Types in previous quarters)
 
- ITEM_WID			-	Unique ID for an ITEM. This column refers to ITEM_WID in table FINANCIALS.MARVELL_DEMO.ITEM_DETAILS
- AMOUNT			-  	Amount associated with the ITEM , Inventory Value in $	
- QUARTER_NAME			-  	Quarter when Item actual inventory was recorded
- TYPE				-  	Type of Inventory for Actual Items


**Table 2: FINANCIALS.MARVELL_DEMO.INVENTORY_ON_HANDS (Stores inventory on hand for future quarters and the inventory on hand as of end of quarters for previous quarters)
 
- ITEM_WID			-  	Unique ID for an ITEM. This column refers to ITEM_WID in table FINANCIALS.MARVELL_DEMO.ITEM_DETAILS
- AMOUNT			-  	Amount associated with the ITEM, Inventory Value in $
- QUANTITY			-  	Number of ITEM Quantities recorded Per Quarter
- QUARTER_NAME			-  	Quarter when Item inventory was populated
- CUM_YIELD			-  	Cummulative Yield for an Item 
- YIELD_QUANTITY 		-  	"Quantity Yield" for an Item per Quarter against Number of ITEM Quantity

**Table 3: FINANCIALS.MARVELL_DEMO.ITEM_DETAILS (This is ITEM master table stores ITEM Information including their Item WID, Division,BU, ProductLine ETC.)


- ITEM_WID 			-	Unique ID for an ITEM 	
- COMPANY                       -	NAME of the company Item belongs to 
- DIVISION                      -	Division In the company Item belongs to 
- BU                            -	BU In the company Item belongs to, Interchangeable called Organization
- PRODUCT_LINE                  -	Product Line In the company Item belongs to
- SUB_PRODUCT_LINE              -	Sub Product Line In the company Item belongs to
- FINANCIAL_GROUP               -	Financial Group In the company Item belongs to
- PART_NUMBER                   -	Part Number for an ITEM
- ITEM_STAGE                    -	Stage in which Item is currently in Product Life Cycle. 
- ASSY_PART_NUMBER              -	Number when the part of Item is in Assembly stage.
- DIE_PART_NUMBER               -	Number when the part of Item is in Die stage.
- ECCN                          -	ECCN Number for an Item to determine licencing information.
- FAB_PART_NUMBER               -	Number when the part of Item is in FAB stage.
- SCHEDULE_B_NUM                -	Specific Classification Code for Exporting Goods.
- TEST_PART_NUMBER              -	Number when the part of Item is in Test stage.
- PLATFORM                      -	
- BASE_DIE                      -	Item Id for the Die.
- BASE_DIE_REV                  -	Revised Item Id for the Die.
- FAB_HOUSE                     -	Fabrication House Name for the Item.
- DESIGN_COUNTRY                -	Country Name where the Item is Designed.
- MARKETING_ITEM                -	Item Number Associated for  Marketting Reference.
- ITEM_TYPE                     -	Type of Item or Item category
- PLANNER_CODE                  -	PLanner Code for an Item which are up to date with Factory Status.
- INVENTORY_ORGANIZATION        -	Unique Number of Inventory Organization
- COUNTRY_OF_MANUFACTURING      -	Country where Item is Manufactured.
- DEVICE                        -	Device Name of the Item.
- PRODUCT_GROUP                 -	Type of Product for Eg if its Wfr or IC. Here Wfr stands for Wafer and IC stands for Integrated Circuit
- PROJECT_CODE                  -	Project Code Associated with an Item.
- PROJECT_CODE_DESCRIPTION      -	Description of a Project Code.
- PACKAGE_CODE                  -	Package Code for an Item.
- SERVICE_PART_NUMBER           -	Service Part Number for an Item.
- LICENSE_EXCEPTION             -	Export Licence Exception Number for the Item.
- END_MARKET                    -	Describes which category of Market Item belongs to during Sale.  
- SUB_MARKET 			-	Describes which Sub category of Market Item belongs to during Sale.  
- MODEL_NUMBER       		-	Model Number for an ITEM. 
- SPEED                         -	Speed for an Item from performance Characteristics.
- ITEM_TYPE_GROUP               -	Item Group Type for an Item Listed
- MPR_YEAR_CATEGORY             -	MPR YEAR CATEGORY for an Item.
- MPR_YEAR_CATEGORY_GROUP       -	Year Categroy Group for MPR
- MPR_YEAR_CATEGORY_SORTING     -	
- CURRENT_MODEL_NUMBER          -	Current Model Number for an ITEM.
- SALES_COMP_DIVISION           -	Division for the Sales Team doing the Sales for an ITEM.
- SALES_COMP_BU                 -	BU or Organization for the Sales Team doing the Sales for an ITEM.
- SALES_COMP_PRODUCT_LINE       -	Product Line for the Sales Team doing the Sales for an ITEM.
- SALES_COMP_FINANCIAL_GROUP    -	Financial Group for the Sales Team doing the Sales for an ITEM.
- SALES_COMP_SUB_PRODUCT_LINE   -	Sub Product Line for the Sales Team doing the Sales for an ITEM.
- TECHNOLOGY_GROUP              -	Tech Group for an ITEM.
- IDENTIFIED_IP                 -	Intellectual property for an Item.
- BUSINESS_OWNER                -	Busines owner of the ITEM.
- PRODUCT_LINE_MANAGER          -	Line Manager for an ITEM.


**Table 4: FINANCIALS.MARVELL_DEMO.PROJECTED_INVENTORY (Stores projected inventory for future quarters with type of projected inventory)


- ITEM_WID			-   	Unique ID for an ITEM. This column refers to ITEM_WID in table FINANCIALS.MARVELL_DEMO.ITEM_DETAILS
- AMOUNT			-	Amount associated with the ITEM	, Inventory Value in $
- QUARTER_NAME			-   	Quarter when Item inventory	was populated
- TYPE				-   	Type of Inventory for Projected Items
