#include <stdio.h>
#include <string.h>
void MUR_861(int a);
void VAR_862(int b);
void VIN_863(int c);
void ANJ_864(int d);
void AAN_865(int e);
void ARU_866(int f);
int main()

{ int age,res,res1,n,A,B,C,D;
  float height, weight, bmi;
char name,allergy;
char str[4]="YES";//to see if string matches or not
char str1[4];//entered string for allergy
char str2[4];//existing user or not
char str3[4];//for UID
printf("Are you an existing user? YES or NO\n");
scanf("%s",str2);
res1=strcmp(str,str2);
if(res1==1){
    printf("Enter the user name\n");
    scanf("%s",&name);
    printf("Enter you age\n");
    scanf("%d",&age);
     printf("Do you have known allergy:YES or NO?(enter in the given format)\n ");
  scanf("%s",str1);
 res=strcmp(str,str1);
 if(res==0)
 {      printf("Enter your known allergy\n ");
       scanf("\n%s",&allergy);
 }
}
 else if(res1==0){
     printf("Enter UID");
     scanf("%d",&n );
     if(n==861){
     MUR_861(861);
         }
         else if(n==862){
             VAR_862(862);
         }
         else if(n==863){
             VIN_863(863);
         }
         else if(n==864){
             ANJ_864(864);
         }
         else if(n==865){
             AAN_865(865);
         }
         else if(n==866){
             ARU_866(866);
         }
    
 }
 else{
       
    printf("Enter height in meter\n");  
    scanf("%f", &height);  
    printf("Enter weight in kg\n");  
    scanf("%f", &weight);  
  
    bmi = weight / (height * height);  
  
    printf("Your Body Mass Index(BMI) is %f\n", bmi);  
  
    if(bmi < 15)  
    {  
        printf("Your BMI category is: Starvation\n");  
    }  
    else if(bmi >= 15.1 && bmi <= 17.5)  
    {  
        printf("Your BMI category is: Anorexic\n");  
    }  
    else if(bmi >= 17.6 && bmi <= 18.5)  
    {  
        printf("Your BMI category is: Underweight\n");  
    }  
    else if(bmi >= 18.6 && bmi <= 24.9)  
    {  
        printf("Your BMI category is: Ideal\n");  
    }  
    else if(bmi >= 25 && bmi <= 25.9)  
    {  
        printf("Your BMI category is: Overweight\n");  
    }  
    else if(bmi >= 30 && bmi <= 30.9)  
    {  
        printf("Your BMI category is: Obese\n");  
    }  
    else if(bmi >= 40)  
    {  
        printf("Your BMI category is: Morbidly Obese\n");  
    }  
    else if(bmi<0)
    {  
        printf("Wrong entry\n");  
    } 
    else {
      printf("1.Polyuria\n2.Hunger\n3.Blurry vision\n");
    printf("\n4.Runny nose\n5.Sore throat\n6.Mild fever\n");
    printf("\n7.Thickened mucus\n8.Lethargy\n9.Laboured breathing\n");
     printf("\n10.Fatigue\n11.Blood and Mucus in cough\n12.Chest pain\n");
     printf("\n13.Irregular fever\n14.Sweating\n15.High fever\n");
     printf("\n16.Fever\n17.Shivering\n18.Yellow skin\n");
     printf("\n19.Vomiting\n20.Stomach pain\n21.Dehydration\n");
    printf("\n22.Hot and Cold flashes\n23.Headache\n24.Muscle pain\n");
 }
 
  
    
    

printf("Enter the numbers of the symptoms you are suffering from\n");
                                                    //taking input of symptoms from the user
  int a,b,c;
  scanf("%d%d%d",&a,&b,&c);
  if(a==13&&b==14){
      printf("Typhoid\n");
      printf("Tablets advised for typhoid: TCV,ofl-OZ,Ceriplus\n");
  
  }
  else if(b==14&&c==15){
      printf("Typhoid\n");
       printf("Tablets advised for typhoid: TCV,ofl-OZ,Ceriplus\n");
      
  }
  else if(a==13&&c==15){
      printf("Typhoid\n");
       printf("Tablets advised for typhoid: TCV,ofl-OZ,Ceriplus\n");
  }
  else if(a==13&&b==14&&c==15){
      printf("Typhoid\n");
       printf("Tablets advised for typhoid: TCV,ofl-OZ,Ceriplus\n");
  }
 
 else if(a==1&&b==2){
      printf("Diabetes\n");
  printf("Tablets advised for Diabetes: TCV,ofl-OZ,Ceriplus\n");
  }
  else if(b==2&&c==3){
      printf("Diabetes\n");
       printf("Tablets advised for Diabetes: TCV,ofl-OZ,Ceriplus\n");

  }
  else if(a==1&&c==3){
      printf("Diabetes\n");
  
       printf("Tablets advised for Diabetes: TCV,ofl-OZ,Ceriplus\n");

  }
  else if(a==1&&b==2&&c==3){
      printf("Diabetes\n");
  printf("Tablets advised for Diabetes: TCV,ofl-OZ,Ceriplus\n");

  }
   else if(a==4&&b==5){
      printf("Common cold\n");
   printf("Tablets advised for Common cold: Tavist, Vicks, Robafase\n");
  }
  else if(b==5&&c==6){
      printf("Common cold\n");
      printf("Tablets advised for Common cold: Tavist, Vicks, Robafase\n");
      
  }
  else if(a==4&&c==6){
      printf("Common cold\n");
      printf("Tablets advised for Common cold: Tavist, Vicks, Robafase\n");
  }
  else if(a==4&&b==5&&c==6){
      printf("Common cold\n");
      printf("Tablets advised for Common cold: Tavist, Vicks, Robafase\n");
  }
  
   else if(a==7&&b==8){
      printf("Bronchitis\n");
   printf("Tablets advised for Bronchitis: Robitussium, Bhronconu, Tyelenol\n");
  }
  else if(b==8&&c==9){
      printf("Bronchitis\n");
      printf("Tablets advised for Bronchitis: Robitussium, Bhronconu, Tyelenol\n");
      
  }
  else if(a==1&&c==9){
      printf("Bronchitis\n");
      printf("Tablets advised for Bronchitis: Robitussium, Bhronconu, Tyelenol\n");
  }
  else if(a==7&&b==8&&c==9){
      printf("Bronchitis\n");
      printf("Tablets advised for Bronchitis: Robitussium, Bhronconu, Tyelenol\n");
  }
      else if(a==10&&b==11){
      printf("Tuberculosis\n");
      printf("Tablets advised for Tuberculosis: Rifampin capsule, Ethambutol, Penicilllin\n");
  
  }
  else if(b==11&&c==12){
      printf("Tuberculosis\n");
      printf("Tablets advised for Tuberculosis: Rifampin capsule, Ethambutol, Penicilllin\n");
  }
  else if(a==10&&c==12){
      printf("Tuberculosis\n");
      printf("Tablets advised for Tuberculosis: Rifampin capsule, Ethambutol, Penicilllin\n");
  }
  else if(a==10&&b==11&&c==12){
      printf("Tuberculosis\n");
      printf("Tablets advised for Tuberculosis: Rifampin capsule, Ethambutol, Penicilllin\n");
  }
        else if(a==16&&b==17){
      printf("Cholera\n");
      printf("Tablets advised for Cholera: Evichol, Shanchol, Anti-Hog cholorer serum\n");
  
  }
  else if(b==17&&c==18){
      printf("Cholera\n");
      printf("Tablets advised for Cholera: Evichol, Shanchol, Anti-Hog cholorer serum\n");
      
  }
  else if(a==16&&c==18){
      printf("Cholera\n");
      printf("Tablets advised for Cholera: Evichol, Shanchol, Anti-Hog cholorer serum\n");
  }
  else if(a==16&&b==17&&c==18){
      printf("Cholera\n");
      printf("Tablets advised for Cholera: Evichol, Shanchol, Anti-Hog cholorer serum\n");
  }
          else if(a==19&&b==20){
      printf("Dysentry\n");
      printf("Tablets advised for Dysentry: Diasyl, NORflox acim, Gluconil\n");
  
  }
  else if(b==20&&c==21){
      printf("Dysentry\n");
       printf("Tablets advised for Dysentry: Diasyl, NORflox acim, Gluconil\n");
      
  }
  else if(a==19&&c==21){
      printf("Dysentry\n");
       printf("Tablets advised for Dysentry: Diasyl, NORflox acim, Gluconil\n");
  }
  else if(a==19&&b==20&&c==21){
      printf("Dysentry\n");
       printf("Tablets advised for Dysentry: Diasyl, NORflox acim, Gluconil\n");
  }
            else if(a==22&&b==23){
      printf("Malaria\n");
       printf("Tablets advised for Malaria: Chloroquil, Quinestor, Morphin\n");
  
  }
  else if(b==23&&c==24){
      printf("Malaria\n");
      printf("Tablets advised for Malaria: Chloroquil, Quinestor, Morphin\n");
  }
  else if(a==22&&c==24){
      printf("Malaria\n");
      printf("Tablets advised for Malaria: Chloroquil, Quinestor, Morphin\n");
  }
  else if(a==22&&b==23&&c==24){
      printf("Malaria\n");
      printf("Tablets advised for Malaria: Chloroquil, Quinestor, Morphin\n");
  }
  else{
      printf("\nThe symptoms mentioned are very close to other diseases, kindly refer to a doctor.\n");
  }
  }
    return 0;  
}
void MUR_861(int a)
{
    printf("\nName of the patient:Murnal\n" );
    printf("\nAge:20\n" );
    printf("\nGender:Female\n" );
    printf("\nBlood group:O+\n" );
    printf("\nPrevious treatment record\n" );
    printf("\nSuffered from Thyphoid from 10/11/2005 to 09/12/2005\n");
    printf("\nTreated by: Dr.Radha\n" );
    printf("\nAllergies:Sulfa drugs \n" );
    
}
void VAR_862(int b){
    printf("\nName of the patient:Varun\n" );
    printf("\nAge:23\n" );
    printf("\nGender:M\n" );
    printf("\nBlood group:AB+\n" );
    printf("\nPrevious treatment record:\n" );
    printf("\nSuffered from Tuberculosis from 6/05/2019 to 23/12/2020\n ");
    printf("\nTreated by: Dr. Anjali\n" );
    printf("\nAllergies:No allergies\n" );
}
void VIN_863(int c){
    printf("\nName of the patient:Vinod\n" );
    printf("\nAge:17\n" );
    printf("\nGender:M\n" );
    printf("\nBlood group:B+\n" );
    printf("\nPrevious treatment record:\n" );
    printf("\nSuffered from Dengue from 16/07/2017 to 30/07/2017\n ");
    printf("\nTreated by: Dr. Bose\n" );
    printf("\nAllergies: Skin Rashes from Aspirin\n" );
}
void ANJ_864(int d){
    printf("\nName of the patient:ANJALI\n" );
    printf("\nAge:19\n" );
    printf("\nGender:Female\n" );
    printf("\nBlood group:B+\n" );
    printf("\nPrevious treatment record\n" );
    printf("\nSuffered from Malaria from 10/11/2005 to 15/12/2005\n");
    printf("\nTreated by: Dr.Radha\n" );
    printf("\nAllergies:Irritation from Penicillin tablets\n" );
}
void AAN_865(int e){
    printf("\nName of the patient:AANYA\n" );
    printf("\nAge:45\n" );
    printf("\nGender:Female\n" );
    printf("\nBlood group:A+\n" );
    printf("\nPrevious treatment record\n" );
    printf("\nSuffered from Diarrhea from 10/11/2005 to 15/11/2005\n");
    printf("\nTreated by: Dr.Radha\n" );
    printf("\nAllergies:Irritation from Penicillin \n" );
}
void ARU_866(int f){
    printf("\nName of the patient:Arun\n" );
    printf("\nAge:30\n" );
    printf("\nGender:M\n" );
    printf("\nBlood group:A+\n" );
    printf("\nPrevious treatment record:\n" );
    printf("\nSuffered from Cholera from 13/04/2018 to 19/04/2018\n ");
    printf("\nTreated by: Dr. Reddy\n" );
    printf("\nAllergies: Swelling and joint aches from Morphine tablets\n" );
}
