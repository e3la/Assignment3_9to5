classDiagram
      
class dbo_datatype {
    data_type_code
          data_type_text
          
}
class dbo_seasonal {
    industry_code
          seasonal_text
          
}
class dbo_supersector {
    supersector_code
          supersector_name
          
}
class dbo_footnote {
    footnote_code
          footnote_text
          
}
class dbo_january_2017 {
    footnote_codes
          id
          original_file
          period
          series_id
          value
          year
          
}
class dbo_annual_2016 {
    footnote_codes
          id
          original_file
          period
          series_id
          value
          year
          
}
class dbo_series {
    data_type_code
          industry_code
          seasonal
          series_id
          series_title
          supersector_code
          
}
class dbo_period {
    month
          month_abbr
          period_code
          
}
class dbo_industry {
    display_level
          id
          industry_code
          industry_name
          naics_code
          publishing_status
          selectable
          sort_sequence
          
}
      