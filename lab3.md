# Lab Report 3

* ## 4 interesting command-line options to use grep
    
    **1. use the -r option**
    
    ```js
    zhuyichen@zhuyichendeMBP skill-demo1-data-main % grep -r "Lucayans" written_2        
    
    written_2/travel_guides/berlitz2/Bahamas-History.txt:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
    written_2/travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.

    ```
    
    **2. use the -v option**
    
    ```js
    zhuyichen@zhuyichendeMBP Abernathy % grep -v "in" ch3.txt
    
    The Retail Challenge
    Product Proliferation
    Retail Overcapacity
    The Retail Fallout
    —William Howell, Chairman, J.C. Penney, 1995
    Mass Merchants: Wal-Mart
    Department Stores: Dillard’s and Federated
    ```
    
    ```js
    zhuyichen@zhuyichendeMBP Abernathy % grep -v "the" ch1.txt

    Five Decades of Change
    A Dying Industry—or Not?
    The Channel Perspective: Five Propositions
    Proposition 1:  The retail, apparel, and textile sectors are increasingly linked as a channel through information and distribution relationships.
    Similar dynamics are cropping up in nonclothing areas as well. Grocery stores now stock a profusion of toothbrushes, Home Depot has shelves and shelves     of different light bulbs, and Dell offers custom-configured personal computers. The growing presence of fashion-basic elements in myriad consumer           products means that all retailers and suppliers may find new competitive opportunities using replenishment.
    How This Book Is Organized
    ```
    
    **3. use the -c options**
    
    ```js
    zhuyichen@zhuyichendeMBP Abernathy % grep -c "in" ch3.txt
    
    54
    ```
    
    ```js
    zhuyichen@zhuyichendeMBP Abernathy % grep -c "Significantly" ch2.txt 
    
    1
    ```
    
    **4. use the -i option**
    
    ```js
    zhuyichen@zhuyichendeMBP Abernathy % grep -w "Chairman" ch3.txt
    
    —William Howell, Chairman, J.C. Penney, 1995
    ```
    
    ```js
    zhuyichen@zhuyichendeMBP Abernathy % grep -w "Significantly" ch2.txt
    
    Significantly, it was in several of these [labor-intensive] more fragmented industries—textiles, apparel, furniture, and some food processing—that the mass retailer (the department stores, mail-order houses and chain stores) began to coordinate the flow of goods from manufacturer to consumer. In those industries where substantial economies of scale and scope did not exist in production, high-volume flows through the processes of production and distribution came to be guided—and the resulting cost reductions achieved—by the buying departments of mass retailers, retailers who handled a variety of related products through their facilities.43
    ```
