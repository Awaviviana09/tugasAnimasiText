unit ANIMASI;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, ExtCtrls, StdCtrls, jpeg, Buttons;

type
  TForm1 = class(TForm)
    Panel1: TPanel;
    Button1: TButton;
    Button2: TButton;
    Button3: TButton;
    Timer1: TTimer;
    Timer2: TTimer;
    Timer3: TTimer;
    Timer4: TTimer;
    Label2: TLabel;
    Image1: TImage;
    Label3: TLabel;
    Label4: TLabel;
    BitBtn1: TBitBtn;
    procedure FormCreate(Sender: TObject);
    procedure Button1Click(Sender: TObject);
    procedure Timer1Timer(Sender: TObject);
    procedure Timer2Timer(Sender: TObject);
    procedure Timer3Timer(Sender: TObject);
    procedure Timer4Timer(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
    procedure Button4Click(Sender: TObject);
    procedure BitBtn1Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;
  jumChar: Integer;

implementation

{$R *.dfm}

procedure TForm1.FormCreate(Sender: TObject);
begin

timer1.Enabled := false;
label3.Caption := '"Unlock Knowledge, Explore Boundless Worlds!"';
button1.Caption := 'Blink';

timer2.Enabled := false;
timer3.Enabled := false;
label2.Caption := ' WELCOME TO MY LIBRARY ';
button2.Caption := 'Marque';

timer4.Enabled := false;
label4.Caption := 'Discover, Learn, Grow: Your Journey Starts Here';
button3.Caption := 'Typing';

end;

procedure TForm1.Button1Click(Sender: TObject);
begin

if button1.Caption = 'Blink' then
 begin
 timer1.Enabled := true;
 button1.Caption := 'Stop';
 end
else if button1.Caption = 'Stop' then
FormCreate(Sender);

end;

procedure TForm1.Timer1Timer(Sender: TObject);
begin
if label3.Visible then label3.Visible := false
else label3.Visible := true;
end;

procedure TForm1.Timer2Timer(Sender: TObject);
begin
label2.Left := label2.Left+1;
if (label2.Left >= 200) then
begin
 timer2.Enabled := false;
 timer3.Enabled := true;
 label2.Left := label2.Left+1;
end
end;

procedure TForm1.Timer3Timer(Sender: TObject);
begin
label2.Left := label2.Left - 1;
if (label2.Left <= 30) then
begin
 timer2.Enabled := true;
 timer3.Enabled := false;
 label2.Left := label2.Left-1;

end
end;

procedure TForm1.Timer4Timer(Sender: TObject);
begin
jumChar := Length(label4.Caption);
case jumChar of
  1 : label4.Caption := label4.Caption + 'M';
  2 : label4.Caption := label4.Caption + 'Y';
  3 : label4.Caption := label4.Caption + ' ';
  4 : label4.Caption := label4.Caption + 'L';
  5 : label4.Caption := label4.Caption + 'I';
  6 : label4.Caption := label4.Caption + 'B';
  7 : label4.Caption := label4.Caption + 'R';
  8 : label4.Caption := label4.Caption + 'A';
  9 : label4.Caption := label4.Caption + 'R';
  10 : label4.Caption := label4.Caption + 'Y';
  11 : label4.Caption := label4.Caption + ' ';
  12 : label4.Caption := label4.Caption + 'Z';
  13 : label4.Caption := label4.Caption + 'A';
  14 : label4.Caption := label4.Caption + 'H';
  15 : label4.Caption := label4.Caption + '2';
  16 : label4.Caption := label4.Caption + ' ';
  17 : label4.Caption := label4.Caption + ' ';
  18 : label4.Caption := ' ';

end
end;

procedure TForm1.Button2Click(Sender: TObject);
begin
if button2.Caption = 'Marque' then
  begin
  timer2.Enabled := true;
  timer3.Enabled := false;
  button2.Caption := 'Stop';
  end
else if button2.Caption = 'Stop' then
  FormCreate(Sender);

end;

procedure TForm1.Button3Click(Sender: TObject);
begin
if button3.Caption = 'Typing' then
  begin
  timer4.Enabled := true;
  button3.Caption := 'Stop';
  end
else if button3.Caption = 'Stop' then
  FormCreate(Sender);
end;

procedure TForm1.Button4Click(Sender: TObject);
begin
if(application.MessageBox('Yakin akan keluar dari program','Konfirmasi',MB_YesNo)=ID_Yes)then
    begin
      close;
      end;
end;

procedure TForm1.BitBtn1Click(Sender: TObject);
begin
if(application.MessageBox('Yakin akan keluar dari program','Konfirmasi',MB_YesNo)=ID_Yes)then
    begin
      close;
      end;
end;

end.
