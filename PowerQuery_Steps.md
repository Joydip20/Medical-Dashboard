#"Changed Type" = Table.TransformColumnTypes(Source, {{"Age", Int64.Type}, {"Billing Amount", Currency.Type}}),
#"Added Custom" = Table.AddColumn(#"Changed Type", "Length of Stay", each Duration.Days([Discharge Date] - [Date of Admission]))
