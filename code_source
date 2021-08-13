#include <stdio.h>
#include<string.h>

void Menu(int a){
	puts("================================================");
	puts("       Rumah Makan Padang Jaya Jaya Jaya        ");
	puts("================================================");
	puts("                  LIST MENU                     ");
	puts("================================================");
	puts(" NAME OF PRODUCT         ||Price                ");
	puts(" 1. Rendang              ||Rp.25000             ");
	puts(" 2. Ayam Pop             ||Rp.20000             ");
	puts(" 3. Gulai Kikil          ||Rp.20000             ");
	puts(" 4. Gulai Otak           ||Rp.20000             ");
	puts(" 5. Gulai Telur Ikan     ||Rp.22000             ");
	puts(" 6. Paru Goreng          ||Rp.18000             ");
	puts(" 7. Telur Balado         ||Rp.9000              ");
	puts(" 8. Sambal Ijo           ||Rp.3000              ");
	puts(" 9. Sate Padang          ||Rp.25000             ");
	puts("10. Nasi Putih           ||Rp.7000              ");
	puts("================================================");

}
	
	
void PesanMakanan(int qty[10], int harga[10]){
	bool tambahPesanan = true;
	char mautambah;
	int nomormakanan;
	
	for(int i=0; i<10; i++){
		qty[i]=0;
	}
	
	while(tambahPesanan){
		puts("Masukan nomor makanan :");
		scanf("%d", &nomormakanan);
		getchar();
		switch(nomormakanan){
			case 1:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[0]);
				qty[0]+=qty[0];
				break;
			case 2:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[1]);
				qty[1]+=qty[1];
				break;
			case 3:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[2]);
				qty[2]+=qty[2];
				break;
			case 4:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[3]);
				qty[3]+=qty[3];
				break;
			case 5:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[4]);
				qty[4]+=qty[4];
				break;
			case 6:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[5]);
				qty[5]+=qty[5];
				break;
			case 7:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[6]);
				qty[6]+=qty[6];
				break;
			case 8:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[7]);
				qty[7]+=qty[7];
				break;
			case 9:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[8]);
				qty[8]+=qty[8];
				break;
			case 10:
				puts("Masukan jumlah yang ingin dipesan :");
				scanf("%d", &qty[9]);
				qty[9]+=qty[9];
				break;
		}
		puts("Apakah mau menambah pesanan ? \n(Klik 'Y' bila ingin menambah pesan dan klik 'N' bila tidak)");
		getchar();
		scanf("%c", &mautambah);
		getchar();
		
		if(mautambah != 'Y'){
		tambahPesanan = false;
		}
	}
	
	for(int i=0; i<10; i++){
		if(qty[i]>0){
			harga[i]=harga[i]*(qty[i]/2);
		}
	}
	return;
}
	

int main(){
	int qty[10];
	
	Menu(0);
	int harga[10]={25000, 20000, 20000, 20000, 22000, 18000, 9000, 3000, 25000,7000};
	
	PesanMakanan(qty, harga);
	puts("");
	for(int i=0; i<10; i++){
		if(qty[i]>0){
			printf("Menu %d\n", i+1);
			printf("Jumlah : %d\n", qty[i]/2);
			printf("Harga : Rp %d\n", harga[i]);
			puts("");
		}
    }
    
    int total=0;
    for(int i=0; i<10; i++){
    	if(qty[i]>0){
    		total+=harga[i];
		}
	}
    printf("Total : Rp %d\n", total);
    
	return 0;
}
