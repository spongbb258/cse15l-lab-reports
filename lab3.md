# Lab Report 3

* ## 4 interesting command-line options to use grep
    
    **1. use the -r option**
    
        Using the **-r** option, it will search for the word that we put on the command and use "" to represent the word we want to search, and then it will search in all files under the directory and its subdirectories. This command-line option is useful because it can help us to find a specific words in a directory or among files.
    
    ```js
    zhuyichen@zhuyichendeMBP skill-demo1-data-main % grep -r "Lucayans" written_2        
    
    written_2/travel_guides/berlitz2/Bahamas-History.txt:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
    written_2/travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.

    ```
    
    ```js
    zhuyichen@zhuyichendeMBP skill-demo1-data-main % grep -r "Lydia" written_2
    
    written_2/non-fiction/OUP/Berk/ch1.txt:•Bob and Sharon, parents of a 4-year-old: Our daughter, Lydia, could recite her ABCs and count from 1 to 20 by age 2 1/2. When we looked for a preschool, many programs appeared to do little more than let children play, so we chose one with lots of emphasis on academics. To me, Lydia’s preschool seems like great preparation for kindergarten and ﬁrst grade, but each morning, Lydia hates to go. Why is Lydia, who’s always been an upbeat, curious child, so unhappy?
    written_2/non-fiction/OUP/Berk/ch1.txt:Recall 4-year-old Lydia’s dislike of her academic preschool, described at the beginning of this chapter. Lydia’s negative reaction is certainly consistent with research ﬁndings. The behaviorist presumption that development can be mechanically engineered by social input, guaranteeing brighter, socially more mature children, is not borne out by the evidence.
    written_2/travel_guides/berlitz1/HistoryIstanbul.txt:        Lydians and Persians
    written_2/travel_guides/berlitz1/HistoryIstanbul.txt:        Inland from Ionia lived the wealthy and powerful Lydians,
    written_2/travel_guides/berlitz1/HistoryIstanbul.txt:        expansionism brought the bulk of Ionia under Lydian rule, but also
    written_2/travel_guides/berlitz1/HistoryIstanbul.txt:        With Lydia defeated, the Greek coastal cities lay open to
    written_2/travel_guides/berlitz1/WhereToIstanbul.txt:        The site of Sardis, the former capital of ancient Lydia,
    written_2/travel_guides/berlitz1/WhereToIstanbul.txt:        Afyon. The Lydians invented coinage, producing the first-ever coins of
    written_2/travel_guides/berlitz1/WhereToIstanbul.txt:        born in S myrna during this period. After the Lydian conquest of the
    written_2/travel_guides/berlitz1/WhereToIstanbul.txt:        Lydians, the Persians, and the Attalid kings of Pergamum, until 133
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
