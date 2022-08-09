# UAS-ALGORITMA_1214013_Muhammad-Dedi-Prasada
keycontrol();  public void keycontrol()     {         if(Greenfoot.isKeyDown("d"))         {             move(5);         }                  if(Greenfoot.isKeyDown("a"))         {             move(-5);         }                  if(Greenfoot.isKeyDown("s"))         {             setLocation(getX(),getY()+5);         }                  if(Greenfoot.isKeyDown("w"))         {             setLocation(getX(),getY()-5);         }              }
Penjelasan terdapat pada kode kode diatas menunjukkan untuk proses jalan nya suatu objek atau yang bisa kita sebut objek itu adalah "lebah". dimana yang kita tau
kode kode diatas itu menunjukkan proses bisa berjalannya suatu objek "lebah".
{
        if(Greenfoot.isKeyDown("d"))
        {
            move(5); 

kode ini untuk perintah jalan ke kanan

if(Greenfoot.isKeyDown("a"))
kode ini untuk perintah jalan ke kiri

 if(Greenfoot.isKeyDown("s"))
kode ini untuk perintah jalan ke bawah

 if(Greenfoot.isKeyDown("w"))
kode ini untuk perintah jalan ke atas
