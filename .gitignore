#include <iostream>
#include <stdlib.h>
#include <string.h>
#include <string>
#include <strings.h>
#include <fstream>
using namespace std ;

int mablag;
class Apelsin{
	public:
		int pul ,xayriya_money , aloqa_type , beeline_money , ucell_money , uzmobile_money , ums_money , humans_money , karta_type, uzcard_money , humo_money , visa_money , xayriya_type;
		string beeline , ucell , uzmobile , ums , humans , uzcard , humo , visa;
		string a[4] = {"Kommunal" , "Aloqa" , "Kartaga" , "Xayriya" };
		string kommunal[5] = {"Elektr Energiya" , "Suv ta'minoti" , "Suyultirilgan Gaz" , "Axlat tashish"} ;
		string aloqa[5] = {"Beeline" , "Ucell" , "Uzmobile" , "UMS" , "Humans"} ;
		string karta[3] = {"Humo" , "Uzcard" , "Visa"} ;
		string xayriya[6] = {"Mehr-shafqat" , "Ezgu Amal" , "Ajr sahovat" , "Qalb ko'zi" , "Vaqf.uz" , "Yurak Amri"} ;
};



int main(){
    Apelsin obj ;
    long long int elektr , suv , gaz , axlat ;
    int pul , payment_type , kommunal_type,  main ;
    cout << "Assalomu Alaykum ! \nBu Dastur To'lov tizimi Vazifasini Bajaradi \n";
    cout << "Balansingizda qancha mablag' borligini kiriting \n" ;cin >> pul;
    z:
    cout << "Quyidagilardan birini tanlash uchun tartib raqamini kiriting \n" ;
        for(int i = 0 ; i < 4 ; i++){
            cout << i +1 <<": " << obj.a[i] << endl ;
        }
        cin >> payment_type ;
        switch(payment_type){
        case 1:
            cout << "Quyidagilardan birini tanlash uchun tartib raqamini kiriting \n" ;
            for(int i = 0 ; i < 4 ; i++){
                cout << i + 1 <<": " << obj.kommunal[i]<< endl ;
            }
            cin >> kommunal_type ;
            switch(kommunal_type){
            case 1:
                cout<<"To'lov qilinuvchi hisob raqamni kiriting : 7 talik \n" ;
                g:
                cin >> elektr ;
                if(elektr>999999 && elektr<10000000){
                        cout <<"Qancha pul o'tkizasiz \n" ; cin >> obj.pul ;
                if(pul>obj.pul){
                    mablag = pul - obj.pul ;
                    cout << obj.pul <<" so'm o'tkazma muvaffaqiyatli amalga oshirildi \n" ;
                    cout << "Hisobingizda " << mablag << " so'm pul qoldi \n" ;
                    cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                    cin >> main;
                    switch(main){
                    case 1:
                        goto z;
                    case 0:
                        exit(0);
                    }
                }
                else
                    cout <<"Hisobingizda yetarli mablag' mavjud emas \n";
                    cout <<"Hisobingizda " << pul <<" bor. Shunga qarab to'lov qiling \n" ;
                    goto m;
                }
                else
                    cout << "7-xonali son kiriting \n" ;
                goto g;
                m:

                    case 2:
                        suv_son:
                        cout<<"To'lov qilinuvchi hisob raqamni kiriting : 7 talik \n" ;
                    suvv:
                    cin >> suv ;
                    if(suv>999999 && suv<10000000){
                        cout << "Qancha pul o'tkizasiz :\n" ;
                        cin >> obj.pul ;
                        if(obj.pul<pul){
                            mablag = pul - obj.pul ;
                            cout << obj.pul <<" so'm to'lov muvaffaqiyatli amalga oshirildi \n" ;
                            cout << "Hisobingizda " << mablag <<" so'm pul qoldi \n \n" ;
                            cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                    cin >> main;
                    switch(main){
                    case 1:
                        goto z;
                    case 0:
                        exit(0);
                    }

                        }
                        else
                            cout << "Hisobingizda Yetarli mablag mavjud emas \n \n" ;
                        goto suvv;
                    }
                    else
                    cout << "7 xonali son kiriting \n" ;
                    goto suv_son;

                    case 3:
                        suy_gaz:
                        cout<<"Shaxsiy hisob raqamni kiriting : 7 talik \n" ;
                    suyy:
                    cin >> gaz ;
                    if(gaz>999999 && gaz<10000000){
                        cout << "Qancha pul o'tkizasiz :\n" ;
                        cin >> obj.pul ;
                        if(obj.pul<pul){
                            mablag = pul - obj.pul ;
                            cout << obj.pul <<" so'm to'lov muvaffaqiyatli amalga oshirildi \n" ;
                            cout << "Hisobingizda " << mablag <<" so'm pul qoldi \n \n" ;
                            cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                    cin >> main;
                    switch(main){
                    case 1:
                        goto z;
                    case 0:
                        exit(0);
                    }
                        }
                        else
                            cout << "Hisobingizda Yetarli mablag mavjud emas \n \n" ;
                        goto suyy;
                    }
                    else
                    cout << "7 xonali son kiriting \n" ;
                    goto suy_gaz;

                    case 4:
                        axl_t:
                        cout<<"To'lov qilinuvchi hisob raqamni kiriting : 7 talik \n" ;
                    axl:
                    cin >> axlat ;
                    if(axlat>999999 && axlat<10000000){
                        cout << "Qancha pul o'tkizasiz :\n" ;
                        cin >> obj.pul ;
                        if(obj.pul<pul){
                            mablag = pul - obj.pul ;
                            cout << obj.pul <<" so'm to'lov muvaffaqiyatli amalga oshirildi \n" ;
                            cout << "Hisobingizda " << mablag <<" so'm pul qoldi \n \n" ;
                            cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                    cin >> main;
                    switch(main){
                    case 1:
                        goto z;
                    case 0:
                        exit(0);
                    }
                        }
                        else
                            cout << "Hisobingizda Yetarli mablag mavjud emas \n \n" ;
                        goto axl;
                    }
                    else
                    cout << "7 xonali son kiriting \n" ;
                    goto axl_t;

            }
            case 2:
                cout << "Qaysi kompaniyaga to'lov qilasiz \nTartib raqamini kiriting \n";
                for(int i = 0 ; i < 4 ; i++){
                cout << i + 1 <<": " << obj.aloqa[i]<< endl ;
            }
                cin >> obj.aloqa_type ;
                switch(obj.aloqa_type){
                case 1:
                    d:
                    cout << "Beeline foydalanuvchisi raqamini kiriting \nRaqam kiritish tartibi quyidagicha: \n911234567 \n901234567 \n" ;
                    cin >> obj.beeline;
                    if(obj.beeline.length()==9){
                    for(int i = 0 ; i < obj.beeline.length(); i++){
                        if(obj.beeline[0]=='9' && (obj.beeline[1]=='1' || obj.beeline[1]=='0')){
                            cout << "Qancha pul o'tkizasiz : \n" ;
                            cin >>  obj.beeline_money ;
                            if(obj.beeline_money<pul){
                                mablag = pul - obj.beeline_money ;
                                cout << obj.beeline_money <<" so'm to'lov muvaffaqiyatli amalga oshirildi \n" ;
                                cout << "Hisobingizda " << mablag << " so'm pul qoldi \n" ;
                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                cin >> main;
                                switch(main){
                                    case 1:
                                        goto z;
                                    case 0:
                                        exit(0);
                                            }
                            }
                            else
                                cout <<"Hisobda Yetarli mablag mavjud emas ! " ;
                        }
                        else
                            cout << "Beeline raqami kiriting !!! \n" ;
                        goto d;
                    }
                    }
                case 2:
                    u:
                    cout << "Ucell foydalanuvchisi raqamini kiriting \nRaqam kiritish tartibi quyidagicha: \n931234567 \n941234567 \n" ;
                    cout << "998 " ; cin >> obj.ucell ;
                    if(obj.ucell.length()==9){
                    for(int i = 0 ; i < obj.ucell.length() ; i++){
                        if(obj.ucell[i]=='9' && (obj.ucell[i+1]=='3' || obj.ucell[i+1]==4)){
                            cout << "Qancha pul o'tkizasiz : \n" ;
                            cin >>  obj.ucell_money ;
                            if(obj.ucell_money<pul){
                                mablag = pul - obj.ucell_money ;
                                cout << obj.ucell_money <<" so'm to'lov muvaffaqiyatli amalga oshirildi \n" ;
                                cout << "Hisobingizda " << mablag << " so'm pul qoldi \n" ;
                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                    cin >> main;
                    switch(main){
                    case 1:
                        goto z;
                    case 0:
                        exit(0);
                    }
                            }
                            else
                                cout <<"Hisobda Yetarli mablag mavjud emas ! " ;
                        }
                        else
                            cout << "Ucell raqami kiriting !!! \n" ;
                        goto u ;
            }
            }
                                case 3:
                                    q:
                    cout << "Uzmobile foydalanuvchisi raqamini kiriting \nRaqam kiritish tartibi quyidagicha: \n991234567 \n" ;
                    cout << "998 " ; cin >> obj.uzmobile ;
                    if(obj.uzmobile.length()==9){
                    for(int i = 0 ; i < obj.uzmobile.length() ; i++){
                        if(obj.uzmobile[i]=='9' && obj.uzmobile[i+1]=='9' ){
                            cout << "Qancha pul o'tkizasiz : \n" ;
                            cin >>  obj.uzmobile_money ;
                            if(obj.uzmobile_money<pul){
                                mablag = pul - obj.uzmobile_money ;
                                cout << obj.uzmobile_money <<" so'm to'lov muvaffaqiyatli amalga oshirildi \n" ;
                                cout << "Hisobingizda " << mablag << " so'm pul qoldi \n" ;
                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                    cin >> main;
                    switch(main){
                    case 1:
                        goto z;
                    case 0:
                        exit(0);
                    }
                            }
                            else
                                cout <<"Hisobda Yetarli mablag mavjud emas ! " ;
                        }
                        else
                            cout << "Uzmobile raqami kiriting !!! \n" ;
                        goto q ;
            }
            }
                                case 4:
                                    s:
                    cout << "UMS foydalanuvchisi raqamini kiriting \nRaqam kiritish tartibi quyidagicha: \n971234567 \n" ;
                    cout << "998 " ; cin >> obj.ums ;
                    if(obj.ums.length()==9){
                    for(int i = 0 ; i < obj.ums.length() ; i++){
                        if(obj.ums[i]=='9' && obj.ums[i+1]=='7'){
                            cout << "Qancha pul o'tkizasiz : \n" ;
                            cin >>  obj.ums_money ;
                            if(obj.ums_money<pul){
                                mablag = pul - obj.ums_money ;
                                cout << obj.ums_money <<" so'm to'lov muvaffaqiyatli amalga oshirildi \n" ;
                                cout << "Hisobingizda " << mablag << " so'm pul qoldi \n" ;
                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                    cin >> main;
                    switch(main){
                    case 1:
                        goto z;
                    case 0:
                        exit(0);
                    }
                            }
                            else
                                cout <<"Hisobda Yetarli mablag mavjud emas ! " ;
                        }
                        else
                            cout << "UMS raqami kiriting !!! \n" ;
                        goto s ;
            }
            }

                                case 5:
                                    j:
                    cout << "Humans foydalanuvchisi raqamini kiriting \nRaqam kiritish tartibi quyidagicha: \n331234567 \n" ;
                    cout << "998 " ; cin >> obj.humans ;
                    if(obj.humans.length()==9){
                    for(int i = 0 ; i < obj.humans.length() ; i++){
                        if(obj.humans[i]=='3' && obj.humans[i+1]=='3'){
                            cout << "Qancha pul o'tkizasiz : \n" ;
                            cin >>  obj.humans_money ;
                            if(obj.humans_money<pul){
                                mablag = pul - obj.humans_money ;
                                cout << obj.humans_money <<" so'm to'lov muvaffaqiyatli amalga oshirildi \n" ;
                                cout << "Hisobingizda " << mablag << " so'm pul qoldi \n" ;
                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                    cin >> main;
                    switch(main){
                    case 1:
                        goto z;
                    case 0:
                        exit(0);
                    }
                            }
                            else
                                cout <<"Hisobda Yetarli mablag mavjud emas ! " ;
                        }
                        else
                            cout << "Humans raqami kiriting !!! \n" ;
                        goto j ;
            }
            }
            }
                                case 3:
                                    cout <<"Qaysi kartaga to'lov qilasiz : \nRaqamini Kiriting : \n";
                                    cout << "1: UzCard \n2: Humo \n3: Visa \n" ;
                                    cin >> obj.karta_type ;
                                    switch(obj.karta_type){
                                    case 1:
                                        uu:
                                        cout << "Uzcard Karta Raqamini kiriting \nMasalan : 8600123456789112 \n" ;
                                        cin >> obj.uzcard ;
                                        if(obj.uzcard.length()==16){
                                            for(int i=0 ; i < obj.uzcard.length() ; i++){
                                                if(obj.uzcard[0]=='8' && obj.uzcard[1]=='6' && obj.uzcard[2]=='0' && obj.uzcard[3]=='0'){
                                                    um:
                                                    cout << "Qancha O'tkazma amalga oshirasiz \n" ;
                                                    cin >> obj.uzcard_money ;
                                                    if(obj.uzcard_money<pul){
                                                        mablag = pul - obj.uzcard_money  ;
                                                        cout << obj.uzcard_money << " so'm to'lov muvaffaqiyatli amalga oshirildi \n";
                                                        cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                                            cin >> main;
                                                            switch(main){
                                                            case 1:
                                                                goto z;
                                                            case 0:
                                                                exit(0);
                                                            }
                                                            }
                                                    else
                                                        cout << "Hisobda Yetarli mablag' mavjud emas \n" ;
                                                    goto um;
                                                }
                                                else
                                                    cout << "Raqam boshi 8600 bilan boshlansin \n" ;
                                                goto uu ;
                                            }
                                        }
                                        else
                                            cout << "Raqam 16 xonali bo'lishi kerak \n";
                                        goto uu;
                                    case 2:
                                        rm:
                                        cout << "Humo Karta raqamini kiriting \nMasalan : 9860123456789112 \n" ;
                                        cin >> obj.humo ;
                                        if(obj.humo.length()==16){
                                            for(int i=0 ; i < obj.humo.length() ; i++){
                                                if(obj.humo[0]=='9' && obj.humo[1]=='8' && obj.humo[2]=='6' && obj.humo[3]=='0'){
                                                    hu:
                                                    cout << "Qancha O'tkazma amalga oshirasiz \n" ;
                                                    cin >> obj.humo_money ;
                                                    if(obj.humo_money<pul){
                                                        mablag = pul - obj.humo_money ;
                                                        cout << obj.humo_money << " so'm to'lov muvaffaqiyatli amalga oshirildi \n";
                                                        cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                                            cin >> main;
                                                            switch(main){
                                                            case 1:
                                                                goto z;
                                                            case 0:
                                                                exit(0);
                                                            }
                                                    }
                                                    else
                                                        cout << "Hisobda Yetarli mablag' mavjud emas \n" ;
                                                    goto hu;
                                                }
                                                else
                                                    cout << "Raqam boshi 9860 bilan boshlansin \n" ;
                                                goto rm ;
                                            }
                                        }
                                        else
                                            cout << "Raqam 16 xonali bo'lishi kerak \n";
                                        goto rm;
                                    case 3:
                                        vs:
                                        cout << "Visa Karta raqamini kiriting \n" ;
                                        cin >> obj.visa ;
                                        if(obj.visa.length()==16){
                                                vm:
                                                    cout << "Qancha O'tkazma amalga oshirasiz \n" ;
                                                    cin >> obj.visa_money ;
                                                    if(obj.visa_money<pul){
                                                        mablag = pul - obj.visa_money  ;
                                                        cout << obj.visa_money << " so'm to'lov muvaffaqiyatli amalga oshirildi \n";
                                                        cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                                            cin >> main;
                                                            switch(main){
                                                            case 1:
                                                                goto z;
                                                            case 0:
                                                                exit(0);
                                                            }
                                                    }
                                                    else
                                                        cout << "Hisobda Yetarli mablag' mavjud emas \n" ;
                                                    goto vm;
                                                }
                                        else
                                            cout << "Raqam 16 xonali bo'lishi kerak \n";
                                        goto vs;
                                    }
                                    case 4:
                                        cout << "Siz Quyidagi tashkilotlarga xayriya qilishingiz mumkin \n" ;
                                        for(int i = 0 ; i < 6 ; i++){
                                            cout << obj.xayriya[i] << endl ;
                                        }
                                        cin >> obj.xayriya_type ;
                                        switch(obj.xayriya_type){
                                        case 1:
                                            xy:
                                            cout << "Mehr-shavqat tashkilotiga qancha xayriya qilmoqchisiz \n" ;
                                            cin >> obj.xayriya_money ;
                                            if(obj.xayriya_money>pul){
                                                cout << obj.xayriya_money <<" so'm xayriya yuborildi \nAlloh sizdan rozi bo'lsin :) " ;
                                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                                        cin >> main;
                                                        switch(main){
                                                        case 1:
                                                            goto z;
                                                        case 0:
                                                            exit(0);
                                                        }
                                                                                }
                                            else
                                                cout << "Hisobingiz " << obj.xayriya_money <<" dan kam \n" ;
                                            goto xy;
                                        case 2:
                                            ey:
                                            cout << "Ezgu Amal tashkilotiga qancha xayriya qilmoqchisiz \n" ;
                                            cin >> obj.xayriya_money ;
                                            if(obj.xayriya_money>pul){
                                                cout << obj.xayriya_money <<" so'm xayriya yuborildi \nAlloh sizdan rozi bo'lsin :) " ;
                                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                                        cin >> main;
                                                        switch(main){
                                                        case 1:
                                                            goto z;
                                                        case 0:
                                                            exit(0);
                                                        }
                                            }
                                            else
                                                cout << "Hisobingiz " << obj.xayriya_money <<" dan kam \n" ;
                                            goto ey;
                                        case 3:
                                            ay:
                                            cout << "Ajr sahovat tashkilotiga qancha xayriya qilmoqchisiz \n" ;
                                            cin >> obj.xayriya_money ;
                                            if(obj.xayriya_money>pul){
                                                cout << obj.xayriya_money <<" so'm xayriya yuborildi \nAlloh sizdan rozi bo'lsin :) " ;
                                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                                    cin >> main;
                                                    switch(main){
                                                    case 1:
                                                        goto z;
                                                    case 0:
                                                        exit(0);
                                                    }
                                            }
                                            else
                                                cout << "Hisobingiz " << obj.xayriya_money <<" dan kam \n" ;
                                            goto ay;
                                        case 4:
                                            qy:
                                            cout << "Qalb ko'zi tashkilotiga qancha xayriya qilmoqchisiz \n" ;
                                            cin >> obj.xayriya_money ;
                                            if(obj.xayriya_money>pul){
                                                cout << obj.xayriya_money <<" so'm xayriya yuborildi \nAlloh sizdan rozi bo'lsin :) " ;
                                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                                    cin >> main;
                                                    switch(main){
                                                    case 1:
                                                        goto z;
                                                    case 0:
                                                        exit(0);
                                                    }
                                            }
                                            else
                                                cout << "Hisobingiz " << obj.xayriya_money <<" dan kam \n" ;
                                            goto qy;
                                        case 5:
                                            vy:
                                            cout << "Vaqf.uz tashkilotiga qancha xayriya qilmoqchisiz \n" ;
                                            cin >> obj.xayriya_money ;
                                            if(obj.xayriya_money>pul){
                                                cout << obj.xayriya_money <<" so'm xayriya yuborildi \nAlloh sizdan rozi bo'lsin :) " ;
                                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                                    cin >> main;
                                                    switch(main){
                                                    case 1:
                                                        goto z;
                                                    case 0:
                                                        exit(0);
                                                    }
                                            }
                                            else
                                                cout << "Hisobingiz " << obj.xayriya_money <<" dan kam \n" ;
                                            goto vy;
                                        case 6:
                                            yy:
                                            cout << "Yurak Amri tashkilotiga qancha xayriya qilmoqchisiz \n" ;
                                            cin >> obj.xayriya_money ;
                                            if(obj.xayriya_money>pul){
                                                cout << obj.xayriya_money <<" so'm xayriya yuborildi \nAlloh sizdan rozi bo'lsin :) " ;
                                                cout << "Bosh Menyuga o'tish uchun 1 ni bosing aks holda 0 ni \n" ;
                                                    cin >> main;
                                                    switch(main){
                                                    case 1:
                                                        goto z;
                                                    case 0:
                                                        exit(0);
                                                    }
                                            }
                                            else
                                                cout << "Hisobingiz " << obj.xayriya_money <<" dan kam \n" ;
                                            goto yy;
                                        }
}
}






























