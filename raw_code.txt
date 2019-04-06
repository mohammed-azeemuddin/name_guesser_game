#include<iostream>
using namespace std;
class Create
{
	public:	char *res=new char[10];
					 
					 char *choose3()
				    {
						  static char str1[]={"abc"};
						  static char str2[]={"def"};
						  static char str3[]={"ghi"};
						  static char str4[]={"jkl"};
						  static char str5[]={"mno"};
						  static char str6[]={"pqr"};
						  static char str7[]={"stu"};
						  static char str8[]={"vwx"};
						  static char str9[]={"yz"};
						  
						  label3:int x;
								 cin>>x;
						  
						  if(x==1)
								return str1;
							else if(x==2)
								return str2;
							else if(x==3)
								return str3;
							else if(x==4)
								return str4;
							else if(x==5)
								return str5;
							else if(x==6)
							    return str6;
							else if(x==7)
							    return str7;
							else if(x==8)
								return str8;
							else if(x==9)
								return str9;
							else
							{   
							  cout<<"Invalid input\n";
							  goto label3;
							}
							
				    }
					char *choose3z()
					{
							static char str1z[]={"adgjmpsvy"};
						    static char str2z[]={"behknqtwz"};
						    static char str3z[]={"cfilorux"};
						  
						    label3z:int x;
							        cin>>x;
						    if(x==1)
  							  return str1z;
							else if(x==2)
							  return str2z;
							else if(x==3)
				  			  return str3z;
							else
							{  
								cout<<"Invalid input\n";
								goto label3z;
							}
					}
					//}
					//char *choose5z()
					//{

					 char *choose4()
				    {
						  static char str1[]={"abcd"};
						  static char str2[]={"efgh"};
						  static char str3[]={"ijkl"};
						  static char str4[]={"mnop"};
						  static char str5[]={"qrst"};
						  static char str6[]={"uvwx"};
						  static char str7[]={"yz"};
						  
						  label4:int x;
								 cin>>x;
						  
						  if(x==1)
								return str1;
							else if(x==2)
								return str2;
							else if(x==3)
								return str3;
							else if(x==4)
								return str4;
							else if(x==5)
								return str5;
							else if(x==6)
							    return str6;
							else if(x==7)
							    return str7;
							else
							{   
							  cout<<"Invalid input\n";
							  goto label4;
							}
							
				    }
							
					  	char *choose4z()
						{
						    static char str1z[]={"aeimquy"};
						    static char str2z[]={"bfjnrvz"};
						    static char str3z[]={"cgkosw"};
						    static char str4z[]={"dhlptx"};
						  
						    label4z:int x;
							        cin>>x;
						    if(x==1)
  							  return str1z;
							else if(x==2)
							  return str2z;
							else if(x==3)
				  			  return str3z;
							else if(x==4)
						  	  return str4z;
							else
							{  
								cout<<"Invalid input\n";
								goto label4z;
							}
						}
						char *choose5()
						{
						  static char str1[]={"abcde"};
						  static char str2[]={"fghij"};
						  static char str3[]={"klmno"};
						  static char str4[]={"pqrst"};
						  static char str5[]={"uvwxy"};
						  static char str6[]={"z"};
						
							label5:int x;
								   cin>>x;
							if(x==1)
								return str1;
							else if(x==2)
								return str2;
							else if(x==3)
								return str3;
							else if(x==4)
								return str4;
							else if(x==5)
								return str5;
							else if(x==6)
							    return str6;
							 else
							 { 
							   cout<<"Invalid input\n";
							   goto label5;
							 }
						}
				    
				    char *choose5z()
					{
					    static char str1z[]={"afkpuz"};
					    static char str2z[]={"bglqv"};
					    static char str3z[]={"chmrw"};
					    static char str4z[]={"dinsx"};
					    static char str5z[]={"ejoty"};		

					    label5z:int x;
								cin>>x;
						  if(x==1)
							  return str1z;
						  else if(x==2)
							  return str2z;
						  else if(x==3)
							  return str3z;
						  else if(x==4)
							  return str4z;
						  else if(x==5)
							  return str5z;
						  else
						  {  
						    cout<<"Invalid input\n";
  						    goto label5z;
						  }
					}					 
					
					char *choose6()
					{
						  static char str1[]={"abcdef"};
						  static char str2[]={"ghijkl"};
						  static char str3[]={"mnopqr"};
						  static char str4[]={"stuvwx"};
						  static char str5[]={"yz"};
						  
					label6:int x;
						   cin>>x;
						  
						  if(x==1)
								return str1;
							else if(x==2)
								return str2;
							else if(x==3)
								return str3;
							else if(x==4)
								return str4;
							else if(x==5)
								return str5;
							else
							{
								cout<<"Invalid input,try again\n";
								goto label6;
							}
					}
					char *choose6z()
					{
						static char str1z[]={"agmsy"};
					    static char str2z[]={"bhntz"};
					    static char str3z[]={"ciou"};
					    static char str4z[]={"djpv"};
					    static char str5z[]={"ekqw"};
						static char str6z[]={"flrx"};
					label6z:int x;
					        cin>>x;
						  if(x==1)
							  return str1z;
						  else if(x==2)
							  return str2z;
						  else if(x==3)
							  return str3z;
						  else if(x==4)
							  return str4z;
						  else if(x==5)
							  return str5z;
						  else if(x==6)
							  return str6z;
						  else 
						  {  
						    cout<<"Invalid input,try again\n";
							goto label6z;
						  }
						
					}
					char *choose7()
				    {
				      static char str1[]={"abcdefg"};
						  static char str2[]={"hijklmn"};
						  static char str3[]={"opqrstu"};
						  static char str4[]={"vwxyz"};
						  
						  label7:int x;
						         cin>>x;
						  
						  if(x==1)
								return str1;
							else if(x==2)
								return str2;
							else if(x==3)
								return str3;
							else if(x==4)
								return str4;
							else
							{   
							  cout<<"Invalid input\n";
							  goto label7;
							}
							
				    }
					
					char *choose7z()
					{
					    static char str1z[]={"ahov"};
					    static char str2z[]={"bipw"};
					    static char str3z[]={"cjqx"};
					    static char str4z[]={"dkry"};
					    static char str5z[]={"elsz"};
						static char str6z[]={"fmt"};
						static char str7z[]={"gnu"};

					    label7z:int x;
								 cin>>x;
						  if(x==1)
							  return str1z;
						  else if(x==2)
							  return str2z;
						  else if(x==3)
							  return str3z;
						  else if(x==4)
							  return str4z;
						  else if(x==5)
							  return str5z;
						  else if(x==6)
							  return str6z;
						  else if(x==7)
							  return str7z;
						  else
						  {  
						    cout<<"Invalid input\n";
							goto label7z;
	   					}
					}
					char *choose8()
				    {
						  static char str1[]={"abcdefgh"};
						  static char str2[]={"ijklmnop"};
						  static char str3[]={"qrstuvwx"};
						  static char str4[]={"yz"};
						  
						  label8:int x;
						         cin>>x;
						  
						    if(x==1)
								return str1;
							else if(x==2)
								return str2;
							else if(x==3)
								return str3;
							else if(x==4)
								return str4;
							else
							{   
							  cout<<"Invalid input\n";
							  goto label8;
							}
				    }
					
					char *choose8z()
					{
					    static char str1z[]={"aiqy"};
					    static char str2z[]={"bjrz"};
					    static char str3z[]={"cks"};
					    static char str4z[]={"dlt"};
					    static char str5z[]={"emu"};
						static char str6z[]={"fnv"};
						static char str7z[]={"gow"};
						static char str8z[]={"hpx"};

					    label8z:int x;
								 cin>>x;
						  if(x==1)
							  return str1z;
						  else if(x==2)
							  return str2z;
						  else if(x==3)
							  return str3z;
						  else if(x==4)
							  return str4z;
						  else if(x==5)
							  return str5z;
						  else if(x==6)
							  return str6z;
						  else if(x==7)
							  return str7z;
						  else if(x==8)
							  return str8z;
						  else
						  {  
						    cout<<"Invalid input\n";
							goto label8z;
	   					}
					}				
					
				    	
			char *compare1(char *y,char *n)
			{
				for (int i= 0; i<=5; i++)
			    {
				    for (int j= 0; j<=5; j++)
					    {
						    if (y[i] == n[j])
							    {
										res[0]=y[i];
										return res;
							    }		    		
					    }
				}
				
			}
			char *compare2(char *y,char *n)
			{
				for (int i= 0; i<=5; i++)
			    {
				    for (int j= 0; j<=5; j++)
					    {
						    if (y[i] == n[j])
							    {
										res[1]=y[i];
										return res;
							    }		    		
					    }
				}
			}
			char *compare3(char *y,char *n)
			{
				for (int i= 0; i<=5; i++)
			    {
				    for (int j= 0; j<=5; j++)
					    {
						    if (y[i] == n[j])
							    {
										res[2]=y[i];
										return res;
							    }		    		
					    }
				}
			}
			char *compare4(char *y,char *n)
			{
				for (int i= 0; i<=5; i++)
			    {
				    for (int j= 0; j<=5; j++)
					    {
						    if (y[i] == n[j])
							    {
										res[3]=y[i];
										return res;
							    }		    		
					    }
				}
				
			}
			char *compare5(char *y,char *n)
			{
				for (int i= 0; i<=5; i++)
			    {
				    for (int j= 0; j<=5; j++)
					    {
						    if (y[i] == n[j])
							    {
										res[4]=y[i];
										return res;
							    }		    		
					    }
				}
			}
			char *compare6(char *y,char *n)
			{
				for (int i= 0; i<=5; i++)
			    {
				    for (int j= 0; j<=5; j++)
					    {
						    if (y[i] == n[j])
							    {
										res[5]=y[i];
										return res;
							    }		    		
					    }
				}
			}
			char *compare7(char *y,char *n)
			{
				for (int i= 0; i<=5; i++)
			    {
				    for (int j= 0; j<=5; j++)
					    {
						    if (y[i] == n[j])
							    {
										res[6]=y[i];
										return res;
							    }		    		
					    }
				}
			}
			char *compare8(char *y,char *n)
			{
				for (int i= 0; i<=5; i++)
			    {
				    for (int j= 0; j<=5; j++)
					    {
						    if (y[i] == n[j])
							    {
										res[7]=y[i];
										return res;
							    }		    		
					    }
				}
			}
			char *result()
			{
			  return res;
			}
			
};
int main()
{
	Create c1;
    static char alpha[]={'a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z'};
    char *r1,*r2,*r3,*r4,*r5,*r6,*r7,*r8;
	char *p1,*p2,*p3,*p4,*p5,*p6,*p7,*p8;
  	char *n1,*n2,*n3,*n4,*n5,*n6,*n7,*n8;
  	char *res;
    int x;
    labelmain:cout<<"Enter the no of letters your name has\n";
			  cout<<"(Choose a name that contains 3 to 8 letters)\n";
    cin>>x;
	if(x==1)
		{cout<<"Sorry you aren't a secret agent to have one word as your name..\n";
		goto labelmain;}
	else if(x==2)
		{cout<<"Very Short name....Try again\n";
		goto labelmain;}
	else if(x==3)
		
	  {
	      for(int i=0,j=1;i<=25;i++,j++)
				{
				  char s[]={alpha[i],alpha[i+1],alpha[i+2]};
					cout<<j<<"("<<s<<")"<<"\t";
					if(j==5)
						cout<<"\n";
					i=i+2;
				}
		cout<<"\nenter the section in which 1st letter is present"<<endl;	
  	    p1=c1.choose3();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
		p2=c1.choose3();
		cout<<"\nenter the section in which 3rd letter is present"<<endl;	
  	    p3=c1.choose3();
      	cout<<"1.(a,d,g,j,m,p,s,v,y) 2.(b,e,h,k,n,q,t,w,z)\n  3.(c,f,i,l,o,r,u,x)"<<endl;
      	cout<<"\nenter the section in which 1st letter is present"<<endl;
  	    n1=c1.choose3z();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
  	    n2=c1.choose3z();
  	    cout<<"\nenter the section in which 3rd letter is present"<<endl;
  	    n3=c1.choose3z();
		  r1=c1.compare1(p1,n1);
	      r2=c1.compare2(p2,n2);
	      r3=c1.compare3(p3,n3);
	      res=c1.result();
	      cout<<" Your name is Noddy!"<<endl;
	      cout<<"Kidding, Nice to meet you"<<" "<<res<<"!"<<endl;
	  }
    else if(x==4)
	  {
	      for(int i=0,j=1;i<=25;i++,j++)
				{
				  char s[]={alpha[i],alpha[i+1],alpha[i+2],alpha[i+3]};
					cout<<j<<"("<<s<<")"<<"\t";
					if(j==4||j==7)
						cout<<"\n";
					i=i+3;
				}
				cout<<"\nenter the section in which 1st letter is present"<<endl;	
  	    p1=c1.choose4();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
    	  p2=c1.choose4();
    	  cout<<"\nenter the section in which 3rd letter is present"<<endl;	
  	    p3=c1.choose4();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;	
      	p4=c1.choose4();
      	cout<<"1.(a,e,i,m,q,u,y)	2.(b,f,j,n,r,v,z)\n 3.(c,g,k,o,s,w) 4.(d,h,l,p,t,x)"<<endl;
      	cout<<"\nenter the section in which 1st letter is present"<<endl;
  	    n1=c1.choose4z();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
  	    n2=c1.choose4z();
  	    cout<<"\nenter the section in which 3rd letter is present"<<endl;
  	    n3=c1.choose4z();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;
  	    n4=c1.choose4z();
		  r1=c1.compare1(p1,n1);
	      r2=c1.compare2(p2,n2);
	      r3=c1.compare3(p3,n3);
	      r4=c1.compare4(p4,n4);
	      res=c1.result();
	      cout<<" Your name is winnie the pooh!"<<endl;
	      cout<<"Kidding, Nice to meet you"<<" "<<res<<"!"<<endl;
	  }
      	
	  else if(x==5)
	  {
				for(int i=0,j=1;i<=25;i++,j++)
				{
				  char s[]={alpha[i],alpha[i+1],alpha[i+2],alpha[i+3],alpha[i+4]};
					cout<<j<<"("<<s<<")"<<"\t";
					if(j==3||j==7)
						cout<<"\n";
					i=i+4;
				}
		cout<<"\nenter the section in which 1st letter is present"<<endl;	
  	    p1=c1.choose5();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
    	p2=c1.choose5();
    	cout<<"\nenter the section in which 3rd letter is present"<<endl;	
  	    p3=c1.choose5();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;	
      	p4=c1.choose5();
      	cout<<"\nenter the section in which 5th letter is present"<<endl;	
  	    p5=c1.choose5();
  	    cout<<"1.(a,f,k,p,u,z),2.(b,g,l,q,v),3.(c,h,m,r,w)"<<endl;
		cout<<"4.(d,i,n,s,x),5.(e,j,o,t,y)"<<endl;
		cout<<"\nenter the section in which 1st letter is present"<<endl;
  	    n1=c1.choose5z();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
  	    n2=c1.choose5z();
  	    cout<<"\nenter the section in which 3rd letter is present"<<endl;
  	    n3=c1.choose5z();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;
  	    n4=c1.choose5z();
  	    cout<<"\nenter the section in which 5th letter is present"<<endl;
  	    n5=c1.choose5z();
	      r1=c1.compare1(p1,n1);
	      r2=c1.compare2(p2,n2);
	      r3=c1.compare3(p3,n3);
	      r4=c1.compare4(p4,n4);
	      r5=c1.compare5(p5,n5);
	      res=c1.result();
	      cout<<" Your name is potato! "<<endl;
	      cout<<"Kidding, Nice to meet you"<<" "<<res<<"!"<<endl;
	  }
	  else if(x==6)
	  {
		  for(int i=0,j=1;i<=25;i++,j++)
		{
		  char s[]={alpha[i],alpha[i+1],alpha[i+2],alpha[i+3],alpha[i+4],alpha[i+5]};
		  cout<<j<<"("<<s<<")"<<"\t";
		  if(j==2||j==4)
		  cout<<"\n";
		  i=i+5;
		}
		cout<<"\nenter the section in which 1st letter is present"<<endl;	
  	    p1=c1.choose6();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
		p2=c1.choose6();
		cout<<"\nenter the section in which 3rd letter is present"<<endl;	
  	    p3=c1.choose6();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;	
      	p4=c1.choose6();
      	cout<<"\nenter the section in which 5th letter is present"<<endl;	
  	    p5=c1.choose6();
		cout<<"enter the section in which 6th letter is present"<<endl;
		p6=c1.choose6();
		cout<<"1.(a,g,m,s,y) 2.(b,h,n,t,z) 3.(c,i,o,u)\n 4.(e,k,q,w) 5.(f,l,r,x)\n";
		cout<<"Enter the section in which 1st letter is present\n";
		n1=c1.choose6z();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
  	    n2=c1.choose6z();
  	    cout<<"\nenter the section in which 3rd letter is present"<<endl;
  	    n3=c1.choose6z();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;
  	    n4=c1.choose6z();
  	    cout<<"\nenter the section in which 5th letter is present"<<endl;
  	    n5=c1.choose6z();
		cout<<"enter the section in which 6th letter is present"<<endl;
		n6=c1.choose6z();
		  r1=c1.compare1(p1,n1);
		  r2=c1.compare2(p2,n2);
	      r3=c1.compare3(p3,n3);
	      r4=c1.compare4(p4,n4);
	      r5=c1.compare5(p5,n5);
		  r6=c1.compare6(p6,n6);
		  res=c1.result();
		cout<<" Your name is Mickey Mouse!"<<endl;
		cout<<"Kidding, Nice to meet you"<<" "<<res<<"!"<<endl;

	  }
	  else if(x==7)
	  {
		for(int i=0,j=1;i<=25;i++,j++)
		{
		  char s[]={alpha[i],alpha[i+1],alpha[i+2],alpha[i+3],alpha[i+4],alpha[i+5],alpha[i+6]};
		  cout<<j<<"("<<s<<")"<<"\t";
		  if(j==2||j==7)
		  cout<<"\n";
		  i=i+6;
		}
		cout<<"\nenter the section in which 1st letter is present"<<endl;	
  	    p1=c1.choose7();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
		p2=c1.choose7();
		cout<<"\nenter the section in which 3rd letter is present"<<endl;	
  	    p3=c1.choose7();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;	
      	p4=c1.choose7();
      	cout<<"\nenter the section in which 5th letter is present"<<endl;	
  	    p5=c1.choose7();
		cout<<"\nenter the section in which 6th letter is present"<<endl;	
  	    p6=c1.choose7();
		cout<<"\nenter the section in which 7th letter is present"<<endl;	
  	    p7=c1.choose7();
		cout<<"1.(a,h,o,v) 2.(b,i,p,w) 3.(c,j,q,x) 4.(d,k,r,y)\n"; 
		cout<<"5.(e,l,s,z) 6.(f,m,t) 7.(g,n,u)\n";
		cout<<"enter the section in which 1st letter is present\n";
		n1=c1.choose7z();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
  	    n2=c1.choose7z();
  	    cout<<"\nenter the section in which 3rd letter is present"<<endl;
  	    n3=c1.choose7z();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;
  	    n4=c1.choose7z();
  	    cout<<"\nenter the section in which 5th letter is present"<<endl;
  	    n5=c1.choose7z();
		cout<<"\nenter the section in which 6th letter is present"<<endl;
  	    n6=c1.choose7z();
		cout<<"\nenter the section in which 7th letter is present"<<endl;
  	    n7=c1.choose7z();
		  r1=c1.compare1(p1,n1);
		  r2=c1.compare2(p2,n2);
	      r3=c1.compare3(p3,n3);
	      r4=c1.compare4(p4,n4);
	      r5=c1.compare5(p5,n5);
		  r6=c1.compare6(p6,n6);
		  r7=c1.compare7(p7,n7);
	      res=c1.result();
		  cout<<" Your name is anthony gonzalvez !"<<endl;
	      cout<<"Kidding, Nice to meet you"<<" "<<res<<"!"<<endl;
	  }
	  else if(x==8)
	  {
		for(int i=0,j=1;i<=25;i++,j++)
		{
		  char s[]={alpha[i],alpha[i+1],alpha[i+2],alpha[i+3],alpha[i+4],alpha[i+5],alpha[i+6],alpha[i+7]};
		  cout<<j<<"("<<s<<")"<<"\t";
		  if(j==2||j==7)
		  cout<<"\n";
		  i=i+6;
		}
		cout<<"\nenter the section in which 1st letter is present"<<endl;	
  	    p1=c1.choose8();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
		p2=c1.choose8();
		cout<<"\nenter the section in which 3rd letter is present"<<endl;	
  	    p3=c1.choose8();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;	
      	p4=c1.choose8();
      	cout<<"\nenter the section in which 5th letter is present"<<endl;	
  	    p5=c1.choose8();
		cout<<"\nenter the section in which 6th letter is present"<<endl;	
  	    p6=c1.choose8();
		cout<<"\nenter the section in which 7th letter is present"<<endl;	
  	    p7=c1.choose8();
		cout<<"\nenter the section in which 8th letter is present"<<endl;	
  	    p8=c1.choose8();
		cout<<"1.(a,i,q,y) 2.(b,j,r,z) 3.(c,k,s) 4.(d,l,t)\n"; 
		cout<<"5.(e,m,u) 6.(f,n,v) 7.(g,o,w) 8.(h,p,x);\n";
		cout<<"enter the section in which 1st letter is present\n";
		n1=c1.choose8z();
  	    cout<<"\nenter the section in which 2nd letter is present"<<endl;	
  	    n2=c1.choose8z();
  	    cout<<"\nenter the section in which 3rd letter is present"<<endl;
  	    n3=c1.choose8z();
  	    cout<<"\nenter the section in which 4th letter is present"<<endl;
  	    n4=c1.choose8z();
  	    cout<<"\nenter the section in which 5th letter is present"<<endl;
  	    n5=c1.choose8z();
		cout<<"\nenter the section in which 6th letter is present"<<endl;
  	    n6=c1.choose8z();
		cout<<"\nenter the section in which 7th letter is present"<<endl;
  	    n7=c1.choose8z();
		cout<<"\nenter the section in which 8th letter is present"<<endl;
  	    n8=c1.choose8z();
		  r1=c1.compare1(p1,n1);
		  r2=c1.compare2(p2,n2);
	      r3=c1.compare3(p3,n3);
	      r4=c1.compare4(p4,n4);
	      r5=c1.compare5(p5,n5);
		  r6=c1.compare6(p6,n6);
		  r7=c1.compare7(p7,n7);
		  r8=c1.compare8(p8,n8);
	      res=c1.result();
		  cout<<" Your name is Abbu Palaan !"<<endl;
	      cout<<"Kidding, Nice to meet you"<<" "<<res<<"!"<<endl;  
	  }
	  else if(x>8)
	  {
		cout<<"Please try a shorter name between 3-8 letters\n";
		goto labelmain;
	  }
	  else
	  {
		  cout<<"Wrong input\n";
		  exit(0);
	  }
}