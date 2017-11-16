# kile-vim-mode-ukr
Some basic mappings for Kile's vim-mode (Ukrainian)

I love 'vim mode' in kile, but using it with non-latin language is a pain.
As I didn't find a better solution to this, I just added a load of mappings by hand.
And as it took me some time, here is a 'backup' of that.

In order to use it copy the corresponding lines to the `[Kate Vi Input Mode Settings]` section of `~/.kde/share/config/kilerc` :

    [Kate Vi Input Mode Settings]
    Macro Completions=0,0
    Macro Contents=,
    Macro Registers=й,q
    Normal Mode Mapping Keys=а,б,в,г,д,е,ж,з,и,й,к,л,м,н,о,п,р,с,т,у,ф,х,ц,ч,Є,ш,щ,І,Ї,ь,Ґ,ґ,ю,я,А,Б,є,В,і,Г,ї,Д,Е,Ж,З,И,Й,К,Л,М,Н,О,П,Р,С,Т,У,Ф,Х,Ц,Ч,Ш,Щ,Ь,Ю,Я
    Normal Mode Mappings=f,\\,,d,u,l,t,;,p,b,q,r,k,v,y,j,g,h,c,n,e,a,[,w,x,",i,o,S,},m,|,\\\\,.,z,F,<,',D,s,U,],L,T,:,P,B,Q,R,K,V,Y,J,G,H,C,N,E,A,{,W,X,I,O,M,>,Z
    Normal Mode Mappings Recursion=false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false,false
