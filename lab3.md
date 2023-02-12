# Lab Report 3

* ## 4 interesting command-line options to use grep
    
    **1. use the -r option**
    
    ```
    zhuyichen@zhuyichendeMBP skill-demo1-data-main % grep -r "Lucayans" written_2        
    
    written_2/travel_guides/berlitz2/Bahamas-History.txt:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
    written_2/travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.

    ```
    
    **2. use the -v option**
    <style>
    pre {
        background-color: yellow;
        padding: 10px;
    }
    </style>

    
    ```
    zhuyichen@zhuyichendeMBP Abernathy % grep -v "in" ch3.txt
    
    The Retail Challenge
    Product Proliferation
    Retail Overcapacity
    The Retail Fallout
    —William Howell, Chairman, J.C. Penney, 1995
    Mass Merchants: Wal-Mart
    Department Stores: Dillard’s and Federated
    ```
    
    **3. use the -A and -B options**
    
    **4. use the -i option**
