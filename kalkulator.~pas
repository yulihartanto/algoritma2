unit kalkulator;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls;

type
  TForm1 = class(TForm)
    Label1: TLabel;
    Label2: TLabel;
    Edit1: TEdit;
    Edit2: TEdit;
    Button1: TButton;
    Button2: TButton;
    Button3: TButton;
    Button4: TButton;
    Edit3: TEdit;
    Button5: TButton;
    Button6: TButton;
    Label3: TLabel;
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
    procedure Button4Click(Sender: TObject);
    procedure Button5Click(Sender: TObject);
    procedure Button6Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;
  angka1, angka2, hasil : Real;
implementation

{$R *.dfm}

procedure TForm1.Button1Click(Sender: TObject);
begin
//mengambil nilai dari edit1 dan edit2
angka1:=StrToFloat(Edit1.Text);
angka2:=StrToFloat(Edit2.Text);

//proses
hasil:=angka1+angka2;

//keluaran
Edit3.Text:=FloatToStr(hasil);
end;

procedure TForm1.Button2Click(Sender: TObject);
begin
//mengambil nilai dari edit1 dan edit2
angka1:=StrToFloat(Edit1.Text);
angka2:=StrToFloat(Edit2.Text);

//proses
hasil:=angka1-angka2;

//keluaran
Edit3.Text:=FloatToStr(hasil);

end;

procedure TForm1.Button3Click(Sender: TObject);
begin
//mengambil nili dari edit1 dan edit 2
angka1:=StrToFloat(Edit1.Text);
angka2:=StrToFloat(Edit2.Text);

//proses
hasil:=angka1*angka2;

//keluaran
Edit3.Text:=FloatToStr(hasil);

end;

procedure TForm1.Button4Click(Sender: TObject);
begin
//mengambil nili dari edit1 dan edit 2
angka1:=StrToFloat(Edit1.Text);
angka2:=StrToFloat(Edit2.Text);

//proses
hasil:=angka1/angka2;

//keluaran
Edit3.Text:=FloatToStr(hasil);
end;

procedure TForm1.Button5Click(Sender: TObject);
begin
Edit1.Text:=' ';
Edit2.Text:=' ';
Edit3.Text:=' ';
end;

procedure TForm1.Button6Click(Sender: TObject);
begin
close;
end;

end.
