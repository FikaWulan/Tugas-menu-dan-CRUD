object DataModule4: TDataModule4
  OldCreateOrder = False
  Left = 192
  Top = 125
  Height = 150
  Width = 317
  object ZConnection1: TZConnection
    ControlsCodePage = cGET_ACP
    UTF8StringsAsWideField = False
    AutoEncodeStrings = False
    Connected = True
    HostName = 'localhost'
    Port = 3306
    Database = 'db_penjualan'
    User = 'root'
    Protocol = 'mysql'
    LibraryLocation = 'D:\PROJECT\delphiaplikasi\libmysql.dll'
    Left = 56
    Top = 24
  end
  object ZQuery1: TZQuery
    Connection = ZConnection1
    Active = True
    SQL.Strings = (
      'Select * From kategori')
    Params = <>
    Left = 160
    Top = 32
  end
  object DataSource1: TDataSource
    DataSet = ZQuery1
    Left = 248
    Top = 32
  end
end
