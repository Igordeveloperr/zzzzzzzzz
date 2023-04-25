# Работа с sql pascal
  ```
  db := TDbf.Create(nil);
  try{
    db.FilePath := 'path';
    db.TableLevel := 7;
    db.Exclusive:= True;
    with db.FeidDefs do begin
      add('id', );
    end;
  ```
