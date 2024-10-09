# Calculadora-de-perimetro-e-area-XML
Calculadora de perimetro e area XML
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:orientation="vertical"
   android:layout_margin="10dp"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        >
    </LinearLayout>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="CALCULADORA DE PERIMETRO E AREA"
        android:textSize="29sp"
        android:gravity="center"
        tools:layout_editor_absoluteX="0dp"
        tools:layout_editor_absoluteY="-2dp" />

    <EditText
        android:id="@+id/blz"
        android:layout_width="match_parent"
        android:layout_height="wrap_content" />
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        >
<LinearLayout
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:orientation="vertical"
    >

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Largura A"
        android:textSize="24sp"
        tools:layout_editor_absoluteX="7dp"
        tools:layout_editor_absoluteY="110dp" />

    <EditText
        android:id="@+id/lar"
        android:layout_width="160dp"
        android:layout_height="41dp"
        tools:layout_editor_absoluteX="0dp"
        tools:layout_editor_absoluteY="133dp" />
</LinearLayout>
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:layout_marginLeft="20dp"
            >
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Largura B"
        android:textSize="24sp"
        tools:layout_editor_absoluteX="224dp"
        tools:layout_editor_absoluteY="110dp" />

    <EditText
        android:id="@+id/lar1"
        android:layout_width="160dp"
        android:layout_height="41dp"
        tools:layout_editor_absoluteX="224dp"
        tools:layout_editor_absoluteY="133dp" />
    </LinearLayout>

    </LinearLayout>
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        >
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            >
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Largura c"
        android:textSize="24sp"
        tools:layout_editor_absoluteX="7dp"
        tools:layout_editor_absoluteY="246dp" />

    <EditText
        android:id="@+id/lar3"
        android:layout_width="160dp"
        android:layout_height="41dp"
        tools:layout_editor_absoluteX="0dp"
        tools:layout_editor_absoluteY="271dp" />
        </LinearLayout>
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            android:layout_marginLeft="20dp"
            >

        <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Largura D"
        android:textSize="24sp"
        tools:layout_editor_absoluteX="223dp"
        tools:layout_editor_absoluteY="246dp" />

    <EditText
        android:id="@+id/lar5"
        android:layout_width="160dp"
        android:layout_height="41dp"
        tools:layout_editor_absoluteX="208dp"
        tools:layout_editor_absoluteY="271dp" />
        </LinearLayout>


    </LinearLayout>
    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        >
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            >
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="PERIMETRO: "
        android:textSize="24sp"
        tools:layout_editor_absoluteX="7dp"
        tools:layout_editor_absoluteY="340dp" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="00000"
        android:textSize="20sp"
    />
        </LinearLayout>
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
        android:layout_marginLeft="100dp"
            >


    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="AREA:"
        android:textSize="24sp"
        />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="00000"
        android:textSize="20sp"
        />
        </LinearLayout>

    </LinearLayout>
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="ENDEREÇO:"
        android:textSize="24sp"
        />

    <EditText
        android:layout_width="match_parent"
        android:layout_height="32dp"
        android:textSize="24sp" />

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        >
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            >

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="BAIRRO:"
        android:textSize="24sp"
        />

    <EditText
        android:id="@+id/bar"
        android:layout_width="178dp"
        android:layout_height="25dp" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_marginLeft="20dp"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:orientation="vertical"></LinearLayout>


            <TextView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="CIDADE:"
                android:textSize="20sp" />

            <EditText
                android:id="@+id/cid"
                android:layout_width="176dp"
                android:layout_height="wrap_content" />
        </LinearLayout>
    </LinearLayout>
    
                <LinearLayout
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:orientation="vertical"
                    android:layout_marginLeft="20dp"
                    />
    
        <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="OBSERVAÇÕES"
            android:textSize="24sp"
        />

    <EditText
        android:id="@+id/obs"
        android:layout_width="match_parent"
        android:layout_height="wrap_content" />

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_gravity="center"
        >
        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="vertical"
            >
    
    
    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="CANCELAR"
        android:textSize="19sp" />
    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/buto"
        />
        </LinearLayout>

        <LinearLayout
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_marginLeft="20dp"
            android:orientation="vertical">
            
            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:orientation="vertical">
                
            </LinearLayout>

            <Button
                android:layout_width="148dp"
                android:layout_height="wrap_content"
                android:text="SALVAR" 
                android:textSize="19sp"
                />

            <EditText
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:id="@+id/buto2"
/>
        </LinearLayout>    
            
            
</LinearLayout>
