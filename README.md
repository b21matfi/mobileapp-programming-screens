
# Rapport


I denna uppgiften skapade jag en ny activity samt en ny layout som den nya activity använder sig utav. När jag skapade den nya activity så la jag också in så att den 
första activty aktiverar den när man klickar på en knapp. När man klickar på knappen så byter namn till den andra sidan och där finns det någon annan information. 
Det jag gjorde var att man skriver sitt namn och sedan så trycker man på sign in när man har gjort det så kommer man till den andra sidan och på den andra sidan så
ser man det namnet man använde för att logga in och en annan knapp för att logga ut.



```
    // För att första sidan ska byta till andra. 
Intent intent = new Intent(MainActivity.this,ProfileActivity.class);
                startActivity(intent);

                intent.putExtra("Username",Username.getText().toString());
                startActivity(intent);
                
                
                //För att logga ut 
                Signout.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                Log.d("==>", "ProfileActivity button pressed");
                finish();
                
                //Knapp för att logga ut 
                    <Button
        android:id="@+id/myButton_Signout"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"

    android:text="Signout"
    tools:ignore="MissingConstraints"
    tools:layout_editor_absoluteX="161dp"
    tools:layout_editor_absoluteY="225dp" />
```

Bilder läggs i samma mapp som markdown-filen.

![](android.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
