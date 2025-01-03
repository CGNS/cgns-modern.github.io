.. CGNS Documentation files
   See LICENSING/COPYRIGHT at root dir of this documentation sources

.. default-domain:: sids

.. role:: sidskey(code)

.. role:: sidsref(code)


.. _ParticleSolutionFigure:

ParticleSolution Figure 
=======================


.. container:: fighead2
  
   **ParticleSolution Node**
   
   (See :ref:`ParticleZone_t figure <ParticleZoneFigure>`)
   
     

.. container:: columns

  .. container:: left
               
    .. container:: figelem2
        
       .. list-table::
          :class:  figtable
          :stub-columns: 1
          :widths: 38 62
               
          * -  Name:      
            -  Data-name identifier or user defined           
          * -  Label:      
            -  :sidsref:`DataArray_t`            
          * -  Data-Type:      
            -  :sidskey:`DataType`            
          * -  Dimensions:      
            -  :sidskey:`IndexDimension`            
          * -  Dimension Values:       
            -  :sidskey:`DataSize[]`            
          * -  Data:      
            -  Solution quantities           
          * -  Cardinality:      
            -  0, *N*            
          * -  Parameters:      
            -  :sidskey:`DataType` , :sidskey:`IndexDimension` , :sidskey:`DataSize`            
          * -  Child Nodes:      
            -  :ref:`DataArray_t figure <DataArrayFigure>`     

    .. container:: figelem2
        
       .. list-table::
          :class:  figtable
          :stub-columns: 1
          :widths: 38 62
               
          * -  Name:      
            -  :sidskey:`PointRange`            
          * -  Label:       
            -  :sidsref:`IndexRange_t`            
          * -  Data-Type:      
            -  :sidskey:`cgsize_t`            
          * -  Dimensions:      
            -  1           
          * -  Dimension Values:       
            -  2           
          * -  Data:      
            -  :sidskey:`Begin` , :sidskey:`End`            
          * -  Cardinality:      
            -  0,1           
    
    .. container:: figelem2
        
       .. list-table::
          :class:  figtable
          :stub-columns: 1
          :widths: 38 62
               
          * -  Name:      
            -  User defined           
          * -  Label:       
            -  :sidsref:`Descriptor_t`            
          * -  See:      
            -  :ref:`CGNSBase_t figure <CGNSBaseFigure>`     
    
    .. container:: figelem2
        
       .. list-table::
          :class:  figtable
          :stub-columns: 1
          :widths: 38 62
               
          * -  Name:      
            -  :sidskey:`DataClass`            
          * -  Label:       
            -  :sidsref:`DataClass_t`            
          * -  See:      
            -  :ref:`CGNSBase_t figure <CGNSBaseFigure>`     
    
    .. container:: figelem2
        
       .. list-table::
          :class:  figtable
          :stub-columns: 1
          :widths: 38 62
               
          * -  Name:      
            -  :sidskey:`DimensionalUnits`            
          * -  Label:       
            -  :sidsref:`DimensionalUnits_t`            
          * -  See:      
            -  :ref:`DimensionalUnits_t figure <DimensionalUnitsFigure>`     
    
    .. container:: figelem2
        
       .. list-table::
          :class:  figtable
          :stub-columns: 1
          :widths: 38 62
               
          * -  Name:      
            -  User defined           
          * -  Label:       
            -  :sidsref:`UserDefinedData_t`            
          * -  See:      
            -  :ref:`UserDefinedData_t figure <UserDefinedDataFigure>`     

.. note::

   :sidskey:`cgsize_t` is determined by the application from which the node is written. For a 32-bit application, :sidskey:`cgsize_t` will be :sidskey:`I4`, and :sidskey:`I8` for a 64-bit application.


.. last line
