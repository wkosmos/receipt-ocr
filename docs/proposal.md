# Tracking Food Ingredients Purchased with OCR of Receipts

## Context
Keeping track of purchased (and used) food would enable filtering of a recipes database by currently available ingredients.

## Proposal
** Use OCR to detect food and quantity purchased from receipts**

## Dataset
- possibly [RVL-CDIP](http://www.cs.cmu.edu/~aharley/rvl-cdip/)
  - greyscale
  - around 25000
  - largest dimension not exceeding 1000 px
- possibly [ExpressExpense](https://expressexpense.com/view-receipts.php)
  - mostly restaurants
  - colour images
  - most skewed
- possibly http://findit.univ-lr.fr/
  - colour images
  - mostly not so skewed
  - actually intended for fraud detection
- could self-generate
  - existing OCR tech is very good
  - I have saved a lot of grocery reciepts
  - it wouldn't take *all* that long to correct good OCR
  
## MVP
- get appropriately accurate OCR results
- ignore unrecognized ingredients

## Next (in order)

  
  
## references
  [Deep learning for automatic sale receipt understanding](https://hal.archives-ouvertes.fr/hal-01654191/document)
  []()
