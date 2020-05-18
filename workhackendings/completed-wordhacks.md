# Completed WordHacks : Endings

## a \(done\)

~ use root words only & words should never be less than 3 letters or more than 6 letters when root words are overridden 

~ words cannot be more than two syllables before addition of 'a'

```text
YES
b,c,d,f,h,j,i,k,q,s,u,v,x,z, eX

NO
a,o,y,  

Yes BUT...
g
    if word ends with 'ing' and is one syllable then append 'a'
        bling+a - yes
        lying+a - no 

l
    if word ends in 'pel' then append 'la'
        expel+la 

n
    if word ends with 'mn' then do not append with 'a'

p
    if word is under 3 letters and ends eith 'ap' than do not append with 'a'
       gap+a - no
r
    if word is under 3 letters and ends eith 'ar' than do not append with 'a'
        jar+a - no

   (overide root words) if word ends with 'er' and is 2 syllables or less then append with 'a'
        quiver+a - yes
        jumper+a - yes

        cozier+a - no

t 
    if word ends in 'pt' then do not append with 'a'

w
    if words ends in 'aw' then do not append with 'a'
        bylaw+a - no 
        paw+a - no
```

## o \(done\)

```text
YES
b,c,d,f,j,i,k,p,q,t,u,v,x,z

NO
o

Yes BUT...

a
    if word is longer than 3 letters and ends with an 'a' then switch out 'a' for o
        viva > viv+o
        pizza > pizz+o
        extra > extr+o
        yoga > yog+o
        aqua > aquo
eX
    if word ends in 'we' then do not append 'o'
        awe > aweo - no 

g
    if word is less then two syllables then append 'o'
        bling+a - yes
        lying+a - no 

h 
    if word ends in 'ah' then do not append 'o'
        hah+o - no
        yeah+o - no
i
    do not limit words by letter amount
        zuchinni+o still sounds great!

l
    if word ends in 'wl' do append 'o'
        owl+o - no
        bowl+o - no

m
    if words are more than 1 syllable then do not append 'o'
        forum+o - no
        peplum+o - no

n
    if word is one syllable and does not end in 'wn' or 'mn' then append 'o'

r
    if word has more than 6 letters then do not append 'o'
        sizzler+o - no
s
    if word is > 3 letters do not append 'o'
w
    if word is > 3 letters do not append 'o'
y
    if word is > 3 letters then switch out 'y' for 'o'
        jury > juro
        crazy > crazo
        jiffy > jiffo
```

#### if end in 'd', 't', 'p' :

```text
food(lio)
vid(lio)
med(lio)

fit(lio)
bot(lio)

ship(lio)
```

## y

~ must add to root word only

```text
YES
    f,j,l,q,x,z,


NO
    a,c,i,k,o,u,v,y


Yes BUT...

b
    if has a vowel-B at end then append with 'by'

        job+by
        cab+by
        web+by
        pub+by
        blob+by
        herb+by
        scrub+by
d
    if has 'ad' at end and is <4 letters, do not append with 'y'

        mad+dy - no
        sad+dy - no
e
    if word is > 3 letters then append with 'y'

        axe+y - no
        bye+y - no
        bee+y - no

g
    if has a vowel-B at end then append with 'gy'

        jog+gy
        blog+gy
        nag+gy
        dig+gy

h 
    if word ends with 'ah' or 'th', then do not append with 'y'

        yeah+y - no
        hah+y - no

l
    if word ends with 'al' or 'el' then append with 'ly'

        expel+ly
        compel+ly
        equal+ly
m
    if word ends with vowel-m then append with 'my'

        yum+my
        chum+my
        jam+my
        swim+my

    unless word ends with 'oom' then append only with 'y'

n 
    if word ends with 'un', 'an', 'on', 'in' then append with 'ny'

        fan+ny
        bun+ny
        don+ny
        sin+ny

    if word ends with 'en' then do not append with 'y or ny'

p
    if word ends with 'op' then append with 'py'

        hop+py
        slop+py

    if word ends with 'oop' then append with 'y'
r
    if word is > 3 and < 6 letters than append with 'y'

        sizzler+y - no

        quiver+y - yes
        air+y - yes
        baker+y - yes
        
s
    if word ends with 'ss' then append 'y'
        miss+y
        kiss+y
        bliss+y
        sass+y
        
   X if word ends with 'ees' then append 'y'
        trees+y
        bees+y
t
    if word is < 4 letters and ends with consonant-t then append 'y'

        opt+y - yes

        bat+y - no


    if word is > 3 letters then append 'y'

        exhibit+y - yes

wX
    if word ends with 'aw' then do not append 'y'

        gnaw+y
        bylaw+y
```

## co

```text
(use roots or one syllable words unless otherwise noted)


YES

    d,g,j,m,r,s,t,v,w,z

NO
    i,o,q,u,y

Examples & Special Rules...

    a
        if ends in consonant-a and > 2 letters then append 'co'
            pizza > pizzaco
            yoga > yogaco
            bra > braco

    b
        if ends in 'mb' then do not append 'co'
            rib > rib+co
            orb > orb+co

    c
        if < 3 syllabels, then append 'o'
            medic+o
            rec+o

    d
        append 'co'
            squid+co
            mad+co
            end+co

    e
        if ends in 'ye', do not apppend 'co'
            love+co
            fake+co
            axe+co

            bye+co - no 

    f
        if < 3 syllables then append 'co'
            elf+co
            puff+co
            golf+co
            spoof+co
            belief+co

    g
        append 'co'
            young+co
            jog+co
            egg+co

    h
        if ends in 'sh' or 'ch' then append 'co'
            wish+co
            quench+co

    i
        do not append 'co'

    j
        append 'co'
            hajj+co

    k
        if < 3 syallables append 'co'
            wok+co
            ark+co
            kayak+co

    l
        if word is < 1 syllable then append 'ico'
            curl+ico
            eel+ico
            oil+ico
            owl+ico

           if 2 syllables append 'co' 

            equal+co
            evil+co

        if word is > 2 syllables do not append 'ico' or 'co'

    m
        append 'co'
            farm+co
            qualm+co
            swim+co

    n
        if ends in 'wn' do not append 'co'
            own+co - no

            fan+co - yes

    o
        do not append 'co'

    p
        if less than 3 syllables, append 'co'

    q
        do not append 'co'

    r
        append 'co'
            air+co
            fear+co
            jar+co

    s 
        append 'co'
            bis+co
            kiss+co
            bus+co
            bass+co

    t
        append 'co'
            bot+co
            up+co
            plot+co

    u
        do not append 'co'
    v
        append 'co'
            rev+cp
            dev+co

    w
        append 'co'
            wow+co
            crew+co
            grow+co

    x
        if word is < 3 syllables then append 'co'

            inbox+co
            reflex+co
            fix+co
            fox+co
    y
        do not append 'co'

    z
        append 'co'
            buzz+co
            prez+co
```

## ee

```text
if word ends in 'consonant-e', append 'e'
    save+e - savee.shop
    hive+e - hivee.cafe
    page+e - pagee.blog
```

## er

```text
YES
    if ends in any of these letters and word root is found or 
    word is > 2 letters and < 6 letters then add 'er' at the end of the word
    
    f, k, q, v, w, x, z

    half + er
    golf + er
    ark + er
    shack + er
    grow + er
    hex + er
    buzz + er


YES but...

 b,c,d,e,g,h,l,m,n,p,t,y
    
            
    e 
        if word ends with consonant-e then append JUST 'r'
        ~ do not append words with vowel-e
        
            axe+r - yes
            love+r - yes
            daze+r - yes
            
            car+r - no
            
    h 
        if word ends with consonant-h then append 'er'
        ~ do not append words with vowel-h
        
              wish+er - yes
              hitch+er - yes
              quench+er - yes
              
              yeah+er - no
                                        

    *consonants-letter good for all but special rules apply for certain vowel-letter or other cases*

        b
            if ends in vowel-b then append with 'ber'

                blab+ber - yes
                rib+ber - yes
                
                jab+er - no
                
        c
            if word ends with consonant-c or is >3 letters then append 'er'
        
                civic+er - yes
                narc+er - yes
                zinc+er - yes
                arc+er - yes
                
                doc+er - no
                rec+er - no

        d 
            if ends in 'ad' then append with 'der'

                mad+der - yes
                glad+der - yes
                
                pad+er - no

        g
            if ends in vowel-g then append with 'ger'

                jog+ger - yes
                bag+ger - yes
                
                blog+er - no

        l
            if ends in 'pel' then append with 'ler'

                expel+ler - yes
                compel+ler - yes
                

        m
            if ends in vowel-m then append with 'mer'

                charm+mer - yes
                balm+mer - yes
                yum+mer - yes
                swim+mer - yes
                
                prim+er - no

        n
            if ends in vowel-n then append with 'ner'
            except words ending with 'een' which should be appended with 'er'

                fun+ner - yes
                ban+ner - yes
    
                queen+er - yes
                keen+er - yes
    
        p
            if word < 4 letters OR ends in 'ip' then append with 'per'

                up+per - yes
                yep+per - yes

                chip+per - yes
                grip+per - yes

        t
            if ends with vowel-t then append with 'ter'

                bat+ter - yes
                cut+ter - yes
                chat+ter - yes

        y
            if word ends with y and is > 4 lettters then y --> 'ier'

                jumpy --> jumpier
                fuzzy --> fuzzier
                crazy --> crazier

NO
    a,i,o,r, s, u
```

## aro

```text
YES
    B, D, V, G, P, N, J, G, C, Z, F, Q, L, K, X
    
    examples;
        G
        bugaro
        dogaro
        kegaro
    
        C
        picaro
        micaro
        talcaro
        fabricaro
        civicaro
    
        Z
        buzzaro
        prezaro
        jeezaro
    
        F
        golfaro
        chefaro
        elfaro
    
Yes BUT...

    if word ends in consonant-a,i,o then append with 'ro'

        pizz(-a)(aro)
        java ro
        vodka ro
        jojoba ro
        chacha ro
        zebra ro
        burqa ro
    
        eco > ecoro
        zoo > zooro
        mojo > mojoro
        duo > duoro
    
    
        yeti > yetiro
        khaki > khakiro
        chili > chiliro
        mochi > mochiro

 if word ends in consonant-e, drop the e, then append with 'aro'
    
        lov(-e)(aro)
        glov(-e)(aro)
        clov(-e)(aro)
        dom(-e)(aro)
        
    H
        if word ends in 'gh', then do not append 'aro'
        
    T
        if word ends in 'ht' or vowel-h then do append 'aro'
    S
        if word root word is < 4 syllables then append 'aro'
        
              cis+aro
              kiss+aro
              
    M 
        if word is < 3 syllables then append 'aro'
        
            forum+aro
            swim+aro

    Y
        if word > 1 syllable then drop 'y' and append 'aro'
        
            fuzzy > fuzz+aro
            buzzy > buzz+aro
        
        if word = 3 letters then append 'aro'
        
            joy+aro
            boy+aro
       
    NO
        R, U, W, H

```

## aroo

```text
YES
    d,f,j,p,q,v 


Yes BUT...

a
    if ends in consonant-a and is > 3 letters then append 'roo'
    ~ do not append on vowel-a.

        pizza+roo
        viva+roo
        yoga+roo
        zebra+roo

b
    if ends in 'mb' do not append 'aroo', otherwise append on all else.

        herb+aroo - yes
        celeb+aroo - yes

        comb+aro - no

g
    if ends with 'g' then append 'aroo' unless word is more than one syllable
     ~ word root can be max 5 letters, one syllable

        bugaroo
        eggaroo
        figaroo

        no
        wrong+aroo
        lying+aroo
h
    if word > 3 letters sn does not end in 'ah' or 'th' then append with 'aroo'

        wish+aroo
        hitch+aroo
        quench+aroo
l
    if word is one syllable than append 'aroo'

        curl+aroo
        oil+aroo
        eel+aroo
k
    if word is one syllable than append 'aroo'

        yak+aroo
        quirk+aroo
        think+aroo
m
    if word is 3 letters or ends in 'rm', 'im' or 'oom' then append 'aroo'

        yum+aroo
        gym+aroo
        swim+aroo
        zoom+aroo
t
    if word ends with 'pt', 'ght' and/or is > 1 syllable then do not append 'aroo'

        no
            might+aroo
            wept+aroo
            exhibit+aroo
            export+aroo

x
    if word is a <4 letters or a one syllable noun/adjective then append 'aroo'

        yes
            fax+aroo
            fox+aroo
            box+aroo

        no
            inbox+aroo
            coax+aroo

z
    if word is one syllable then append 'aroo'

        yes
            buzz+aroo
            prez+aroo

NO
    c,e,i,n,o,r,s,u,w,
```

## ia

```text
YES
c,d,f,j,i,k,m,p,q,s,w,t,v,x,z


NO
o,u


Yes BUT...

a
    if word is > 3 letters and ends with an consonant-a then switch out 'a' for 'ia'
    ~ word must be > 3 letters

        viva > viv+ia
        pizza > pizz+ia
        extra > extr+ia
        yoga > yog+ia
        aqua > aqu+ia

b
    if ends in 'mb' then do not append 'ia'
    ~ append on all else

        no
            comb+ia
            lamb+ia 

        yes
            herb+ia
            orb+ia
            gab+ia
e
    if word ends in 'we' then do not append 'ia'
    ~ append ia for all else

        awe > aweo - no 

    if word ends in consonant-e then drop the 'e' and append 'ia'

        love+ia
        daze+ia

g
    if word is less then two syllables then append 'ia'

        bling+ia - yes
        lying+ia - no 

h 
    if word ends in 'ah' and/or > 2 syllables then do not append 'ia'

        hah+ia - no
        yeah+ia - no

        zenith+ia - yes
i
    if word ends in 'i' then drop the 'i' and append 'a'
    ~do not limit words by letter amount

        zuchinn+ia still sounds great!

l
    if word ends in 'l' then append 'ia'
    ~ do not limit word length

n
    if word is one syllable and does not end in 'mn' or 'wn' then append 'ia'

        hymn+io - no
        grown+io -no

r
    if word is > 2 syllables then do not append 'ia'

        sizzler+ia - no

y
    if word is > 3 letters then switch out 'y' for 'ia'
        jury > juria
        crazy > crazia
        jiffy > jiffia
```

## io \(done\)

```text
YES
c,d,f,j,i,k,m,p,q,t,v,x,z,


NO
o,u


Yes BUT...

a
    if word is > 3 letters and ends with an consonant-a then switch out 'a' for 'io'
    ~ word must be > 3 letters

        viva > viv+io
        pizza > pizz+io
        extra > extr+io
        yoga > yog+io
        aqua > aqu+io

b
    if ends in 'mb' then do not append 'io'
    ~ append on all else

        no
            comb+io
            lamb+io 

        yes
            herb+io
            orb+io
            sab+io
e
    if word ends in 'we' then do not append 'io'
    ~ append io for all else

        awe > aweo - no 

        love+io
        daze+io

g
    if word is less then two syllables then append 'io'

        bling+io - yes
        lying+io - no 

    if word ends in vowel-g then append 'io' or append 'gio'

        blog+io or blog+gio
        snug+io or snug+gio

h 
    if word ends in 'ah' or 'th' then do not append 'io'

        hah+io - no
        yeah+io - no
        zenith+io - no
i
    if word ends in 'i' then drop the 'i' and append 'o'
    ~do not limit words by letter amount

        zuchinn+io still sounds great!

l
    if word ends in 'al' then do not append 'io'

        equal+io - no

    if word ends in 'il' and is > 1 syllable, then do not append 'io'

        evil+io - no

n
    if word is one syllable and does not end in 'mn' or 'wn' then append 'io'

        hymn+io - no
        grown+io -no

r
    if word  is > 2 syllables then do not append 'io'

        sizzler+io - no
s
    if word ends in 'es' then do not append 'io'
w
    if word is > 4 letters then do not append 'io'
y
    if word is > 3 letters then switch out 'y' for 'io'
        jury > jurio
        crazy > crazio
        jiffy > jiffio
```

## ly \(done\)

```text
YES
        a,b,c,d,f,g,j,i,l,k,p,q,t,u,v,x,z

NO
    o

Yes BUT...

    e
        if word ends in 'ae', 'ie', 'oe', 'ye' then do not append 'ly'

        if word ends in consonant-e or 'ue', 'ee' then append 'ly'

            should we drop the e from 'ue' ?

                revenue > revenu+ly
                true > trul+y

    h
        if word ends in 'th' then do not append 'ly'

            zenith+ly - no

    m
        if word ends in 'sm' then do not append 'ly'

            prism+ly - no

    n 
        if word ends in 'mn' then do not append 'ly'

            hymn+ly - no

    r
        if word > 2 syllables,  then do not append 'ly'

            cozier+ly - no

    s
        if word is true root word ending with 's' then append 'ly'

            cis+ly - yes
            yes+ly - yes
            bass+ly - yes

            junks+ ly - no
            fazes+ly - no

    w
        if word is < 4 letters then append with 'ly'

            grow+ly
            pow+ly
    Xy
        Xif word ends in consonant-y then drop 'y' and append 'ily'

            crazy > craz+ily
            jumpy > jump+ily

        Xif word ends in vowel-y then append 'ly' as normal

            joy+ly
            guy+ly
```

## us \(done\)

```text
YES
    b,c,
        ( do not limit to word root or by syllables)
        celeb+us
        crumb+us
        gastropub+us

        epizootiuc+us
        zinc+us


    d,g,k,m,p,t,v,z 
        (limit to root word only)
        feed+us
        squid+us
        odd+us

        jog+us
        dog+us
        keg+us

        wok+us
        ark+us
        think+us

        yum+us
        swim+us

        pop+us
        shrimp+us
        sheep+us

        next+us
        gift+us
        might+us

        dev+us
        rev+us

        buzz+us
        prez+us
        jeez+us


    h
        if ends in 'ch' or 'ch' then append 'us'
            psych+us
            munch+us
            wish+us

    n
        if ends in 'wn' 'mn' do append 'us'
            fan+us - yes
            bun+us - yes

            hymn+us - no

    x
        if word < 3 syllables then append 'us'
            index+us
            annex+us


NO
    a,e,f,j,i,l,o,q,r,s,u,w,y
```

## ica / ico

```text
YES 
    b,d,i,m,t,v,x,z
        ribi+ca
        orbi+ca
        redub+ica

        odd+ica
        squid+ica

        buzz+ica

        uni+ca
        maxi+ca

        curl+ica

        farm+ica
        prism+ica

        sheep+ica
        pump+ica

        buzz+ica
        prez+ica
        jeez+ica

NO
    y,c,e,f,g,h,j,k,n,o,q,r,u,w,y
```

## ism

```text
YES
    ~no limit on the length of these words
    b,c,d,e,f,j,l,k,m,p,q,u,x

    yoga+ism
    rib+ism
    odd+sim
    love+ism
    hajj+ism
    pal+ism
    snack+ism
    charm+ism
    romp+ism
    flu+ism
    fix+ism

YES But...
    if word ends in 'r','w','z' then append 'ism'
        air+ism
        crew+ism
        prez+ism

    H
        if word ends in consonant-h then append 'ism'
            rich+ism

    I
        if word > 2 letters then append just 'sm'
            yeti+sm

    N
        if word ends in 'mn' or 'wn' then do not append 'ism'


    O
        if word ends in 'yo' then do not append 'ism'

    T
        if word ends in 'ght' then do not append 'ism'

NO
    s,v
```

## ora

```text
YES
    c,d,j,l,k,m,p,q,t,u,v,x,z

NO
    r


Yes But...

    a
        if word is > 3 letters and does not end in 'ha' then drop 'a' and append 'ora'

            data > dat+ora - yes
            yoga > yog+ora - yes
            pizza > pizz+ora - yes

    b
        if word ends in 'mb' or > 1 syllable then do not append 'ora'

            comb+ora - no
            redub+ora - no

    e
        if word < 5 letters and does not end in 'ye', 'ue', 'oe', 'ae', 'we' then append 'ora'

            bee+ora - yes
            love+ora - yes

            should we drop the 'e' ?

                lov e > lovora
                piqu e > piquora
                ax e > axora


            bye+ora - no
            shoe+ora - no
            awe+ora - no 
    f
        if word is > 1 syllable then do not append 'ora'

            chef+ora - yes
            scarf+ora - yes

    g 
        if word is > 1 syllable then do not append 'ora'

            king+ora - yes
            blog+ora - yes
            egg+ora - yes   

    h
        if word ends in vowel-h and/or > 1 syllable, then do no append 'ora'

            yah+ora - no
            zenith+ora - no

            wish+ora - yes

    i 
        if word > 2 letters then append 'ora'

            uni+ora - yes
            cami+ora - yes
            scampi+ora - yes

            hi+ora - no

    n
        if word ends in 'mn', 'wn' then do not append 'ora'

            known+ora - no
            own+ora - no
            hymn+ora - no

    o
        if word ends in 'o', then append just 'ra' 

            jumbo+ra - yes
            eco+ra - yes
            kilo+ra - yes

    s
        if word ends in true 's' in a word root, then append 'ora'

            bus+ora - yes
            bass+ora - yes
            cis+ora - yes

    w
        if word is < 2 syllables then append 'ora'

            pow+ora - yes
            crew+ora - yes 
            wow+ora - yes

    y
        if word ends in 'y' and is > 3 letters then drop 'y' and append 'ora'

            fuzzy > fuzz+ora - yes
            crazy > craz+ora - yes
            jumpy > jump+ora - yes
```

## oora / ura

```text
YES
    b,c,d,j,k,m,q,t,v,x,z

NO
    l,o,r,w

Yes But...
    a
        if word is > 3 letters and ends in consonant-a then append 'oora'

            viva > vivoora
            yoga > yogoora
            pizza > pizzoora

    e
        if word ends in consonant-e and is > 3 letters then drop 'e' and append 'oora'

            daze > dazoora
            zine > zinoora
            hype > hypoora
            prize > prizoora

        if word ends in 'we' then do not append 'oora'

    f
        if word ends in 'ff' or > 1 syllable then do not append 'oora'

            puff > puffoora - no ?
            aloof > aloofoora - no 

    g
        if word is > 1 syllable then do not append 'oora'

    h
        if word is consonant-h (except 'th') then append 'oora'

            quench > quenchoora
            psych > psychoora
            wish > wishoora
    i
        if word is consonant-i and > 3 letters, then drop 'i' and append 'oora' (except 'wi' - do not append)

            maxi > maxoora - yes
            yeti > yetoora - yes

            kiwi > kiwoora - no
    n
        if word ends in 'wn' or 'mn' then do not append 'oora'

    p
        if word is 1 syllable then append 'oora'

            pop+oora - yes
            shrimp+oora - yes
    s
        if word is one syllable then append 'oora'

            cis+oora - yes
            bass+oora - yes
    u
        if word ends in consonant-u then drop the 'u' and append 'oora'

        if word ends in consonant-u then append just 'ra'

            tofu > tof+oora - yes
            sudoku > sudok+oora - yes

            sudoku+ra - yes
            tofu+ra - yes
```

## oro

```text
YES
    a
        if word ends in consonant-a and is > 3 letters then drop 'a' and append 'oro'

            viva > viv+oro
            pizza > pizz+oro
            yoga > yog+oro

    b
        if word ends with 'mb' then do not append 'oro'

            comb > combo+oro - no

    c
        if word > 2 syllables, then do not append 'oro'

            exotic > exotic+oro - no

    d
        if word is < 2 syllables then append 'oro'

            squid+oro - yes
            feed+oro - yes

    e
        if word ends in consonant-e and does not end in 'we' then append 'oro'

            axe > ax+oro
            hype > hyp+oro
            love > lov+oro

    f
        if word ends with 'f' and is < 3 syllables then append 'oro'

            scarf+oro
            aloof+oro
            poof+oro
            chef+oro

    g
        if word is > 1 syllable then do not append 'oro'

            lying+oro - no

            jog+oro - yes

    h
        if word ends in consonant-h and it < 3 syllables then append 'oro'

            zenith+oro - yes
            ash+oro - yes
            wish+oro - yes

    j
        if word ends in j then append 'oro'

    i
        if word is > 3 letters, < 3 syllables, ends in consonant-i (except for 'wi') then drop 'i' and append 'oro'

            kiwi > kiworo - no

            cami > camoro - yes
            chilli > chill+oro - yes
            zuchinni > zuchinn+oro - yes

    l
        if word is < 3 syllables then append 'oro'

            expel+oro
            curl+oro
            eel+oro

    k
        if word ends in 'k' (unless 'ck'), and is 1 syllable, then append 'oro'

            think+oro
            whisk+oro
            quirk+oro

    m
        if word is > 2 syllables then do not append 'oro'

            gym+oro - yes
            zoom+oro - yes

            zarconium+oro - no

    n
        if word ends in 'wn', 'mn' and or is > 2 syllables then do not append 'oro'

            own+oro - no
            hymn+oro - no
            exotoxin+oro - no

    o
        if word ends in 'o' then append just 'ro'
        ~ append on all word length

            chickaboo+ro - yes
            duo+ro - yes

    p
        if word ends in 'p' and < 3 syllables then append 'oro'

    q
        if word ends in 'q' then append 'oro'

    r
        if word ends in 'r' then do not append 'oro'

    s
        if word is < 2 syllables then append 'oro'
    t
        if word is < 4 syllables then append 'oro'

    u
        if word ends in 'u' then do not append 'oro'
    v
        if word ends in 'v' then append 'oro'
    w
        if word ends in 'w' then do not append 'oro'
    x
        if word < 4 syllables then do not append 'oro'
    y
        if word > 3 letters and ends in consonant-y, then drop 'y' and append 'oro'

            jiffy > jiff+oro - yes
            fuzzy > fuzz+oro - yes

    z
        if word is < 3 syllables then append 'oro'

            pizazz+oro - yes

NO
    u,w,r
```

## sy

```text
YES (append only to one syllable words)
    a,b,c, d, e,f,g,l,k,m,t,u,v,w,y


        feed+sy
        squid+sy
        rec+sy
        owl+sy
        curl+sy
        think+sy
        yum+sy
        joy+sy

    N
        if word ends in 'mn' or 'wn' then do not append 'sy'
    P
        if words are < 3 syllable then append 'sy'

            equip+sy
    S
        if words are < 3 syllables then append 'sy'

            annex+sy
            reflex+sy


NO
    h,j,i,o,q,r,y,z
```

## ify

```text
if word ends in 'erse', 'ch', 'nse' then append 'ify'

    diverse > divers (drop-e) + ify = diversify

    lunch > lunchify

    intense > intens (drop-e) + ify = intensify
```

## dom

```text
if word is a short noun < 3 syllables then append 'dom'

    king + dom
    dog + dom
    star + dom
    yuppy + dom
```

## able

```text
if word is a verb and ends in n,x, k, w, y m, p, r, t, w, 'zz' then append '-able'
    n
        not 'mn'
    t
        not 'ght'
```

## ion

```text
if word ends in 'te', 'pt', 'ct', 'ate' then append 'ion'
    note (drop-e) > not+ion
    emote > emot+ion

    erupt > eruption
    disrupt > disrupt+ion

    destruct > destruct+ion
    depict > depict+ion
    subject > subject+ion
    act > action

    create (drope-e) > creat+ion
    migrate > migrat+ion
```

## ation

```text
if word ends in 'ex', 'ax', 'ix', 'orm', 'port' then append 'tion'

    index > index+ation
    relax > relax+ation
    prefix > prefix+ation

    reform > reform+ation
    dorm > dorm+ation

    import > import+ation
```

## ing \(done\)

```text
(only append after nouns & verbs)
if word ends in just one letter then append one more of that letter and 'ing'
    (except when ends in consonant-t, 5 >letters with ed ending,w,x,y,z)
    clap p + ing


if word ends in double letters or [w,x,y,z] then append 'ing'
    miss+ing
    buzz+ing

    wax+ing
    chew+ing
    cry+ing

if word ends with silent e then drop e and append 'ing'
    gaze > gazing
    frizzle > frizzling
```

## ed \(done\)

```text
(only append after verbs)

if word ends in just one letter then append one more of that letter and 'ed'
    (except when ends in consonant-t, 5 >letters with ed ending,w,x,y,z)

    clap+ped

if word ends in double letters or [w,x,y,z] then append 'ed'
    miss+ed
    buzz+ed

if word ends with silent e then drop e and append 'ed'
    gaze > gazed
    frizzle > frizzled
```

## ee

```text
if word ends in 'consonant-e', append 'e'
    save+e - savee.shop
    hive+e - hivee.cafe
    page+e - pagee.blog
```

## uu / oo

```text
if 1 syllable noun ends in 'g', then append 'uu/u' or 'oo'
    mug+uu - mug+oo
    jog+uu - jog+oo
    blog+uu - blog+oo
    veg+uu - veg+oo

    'ck', 'ss', 'sh', 'm', 'zz', 'ff','ub', 've'
        snack+uu - snack+oo
        rack+uu - rack+oo
        kiss+uu - kiss+oo
        chum+uu - chum+oo
        jam+uu - jam+oo
        swim+uu - swim+oo
        fish+uu - fish+oo
        buzz+uu - buzz+oo
        puff+uu - puff+oo
        tub+uu - tub+oo
        clove+uu - clove+oo
        love+uu - love+oo

    
   'k', 'v', 'd', 't' (no ht), 'p','n' (no mn), 'x'
        dev+uu - dev+oo
        feed+uu - feed+oo
        squid+uu - squid+oo
        pup+uu - pup+oo
        kit+uu - kit+oo
        bun+uu - bun+oo
        mix+uu - mix+oo
        
    
```

## ee &gt; y

```text
if word is > 1 syllable then 'ee' > 'y'
    toffee > toffy
    coffee > coffy
    lychee > lychy
    pedigree > pedigry
```

## oon

```text
if 1 syllable ends in 'ck' then append 'un' / 'oon'
    snack+un
    snack+oon

    jam+oon
    jam+un
```

## gie / gy

```text
third consonant is "g"...

if word is one syllable noun of 3 letters then append 'gie' or 'gy'
- unless contains 'ght'

veggie veggy
leggie leggy
piggie piggy
wiggie wiggy
eggie eggy

sight > siggie - NO

if word is one syllable noun of > 3 letters then append 'y' or 'ie'

songy songie
```

## ify \(done\)

```text
if word ends in 'ense' then drop last 'e' and append 'ify'
    expensify.com       expens (-e+i) (fy)
    suspensify.com
    dispensify.com
```

## chy

```text
if word ends in 'ch' then + 'y'   
    crun(ch) > crunchy
    bun(ch) > bunchy
    lun(ch) > lunchy
    pun(ch) > punchy
```

## mmy

```text
if word ends in 'um' and is one syllable then append 'my'
    yum(my)
    rum(my)
    hum(my)
    plum(my)
```

## ny 

```text
if word ends in 'un', 'an', 'oo' then append 'ny'
    fun(ny)
    sun(ny)
    fan(ny)
    bun(ny)
    zoo(ny)
    shun(ny)
    stun(ny)
```

## ic &gt; o

```text
if word ends in consonant-ic then > consonant-o
    eth(nic) > eth(no)
    plas(tic) > plas(to)
    pic(nic) > pic(no)
    pub(lic) > pub(lo)
    ma(gic) > ma(go)
    spora(dic) > spora(do)
    clas(sic) > clas(so)
    arc(tic) > ar(co)
    co(mic) > co(mo)
    cli(nic) > cli(no)
    aero(bic) > ae(ro)
```

## ology

```text
YES
    t,p,n,b,i,l,k,m,n,o,p,u,v,w,x


one syllable
    c,d,e,f,g,j,q,r,s

eg;

noun(ology)
export(ology)
lip(ology)
soul(ology)
inert(ology)
tarp(ology)
crab(ology)
squid(ology)


O
    if ends in 'o' just append 'logy'

        duo+logy - yes

    if ends in 'lo' do not append 'ology'

         jello+logy - no
Y
    if ends in 'y' then do not append 'ology'


zoned(ology) X NO (ed) - get rid of the ed and then
add ology = zonology - this is finding the root I guess

sized > sizology
vexed > vexology
```

