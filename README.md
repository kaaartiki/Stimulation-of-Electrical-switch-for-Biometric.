# Stimulation-of-Electrical-switch-for-Biometric.
This project simulates an electrical switch controlled by fingerprint authentication on a smartphone. It demonstrates secure ON/OFF control using biometric input, ideal for smart home or IoT applications.
#include <stdio.h>
int main() {
    int fingerprint;
    printf("Fingerprint lock Stimulation\n");
    printf("Enter fingerprint data(0=not matched,1=matched)=");
    scanf("%d",&fingerprint);
    if (fingerprint==1){
        printf("FINGERPRINT MATCHED! Phone Unlocked (ON)\n");
    }
    else{
        printf("FINGERPRINT NOT MATCHED! Phone Locked (OFF)\n");
            }
      
     return 0;
}
