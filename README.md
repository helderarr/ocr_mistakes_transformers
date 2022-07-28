# OCR Mistakes Transformers
A model for fixing OCR mistakes originated from diffrent scanners


## Examples

### Original
(random sentences cropped at 100 characters)

**Sentence 1**

*This will make future review easier, as you will have a rough summary to work from. Don’t get too bo*


**Sentence 2**

*You don’t need to write yourself a perfect script, but take a little time and figure out when and ho*


### Scanned 
(3 versions of each sentence scanned by 3 different machines)

**Sentence 1**
-	*marg to worh trom. Doa’t gep poo bo*
-	*is wilt make fture review casier, as yu will hav e o rough suaxary to work from. Don’t gct*
-	*This tll make tupvr reuiew eosie, o'*

**Sentence 2**
-	*tle time aap igure ovt when ond ho*
-	*rfect script, bu t take a llttfe time ad tigue uut*
-	*Yau don’teed to write gourself a berfeot scrlpt*



### Model Output

**Sentence 1**

*This will make review easier, as you will have a rough surface to work from.*

**Sentence 2**

*You don’t want to write yourself a perfect script, but take a little*

