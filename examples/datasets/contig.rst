Example ContigSet XML::

  <?xml version="1.0" encoding="utf-8"?>
  <pbds:ContigSet 
      xmlns:pbbase="http://pacificbiosciences.com/PacBioBaseDataModel.xsd"  
      xmlns:pbds="http://pacificbiosciences.com/PacBioDatasets.xsd" 
      xmlns="http://pacificbiosciences.com/PacBioDataModel.xsd" 
      UniqueId="b095d0a3-94b8-4918-b3af-a3f81bbe519c" 
      TimeStampedName="contigset_150304_231155"
      MetaType="PacBio.DataSet.ContigSet" 
      Name="DataSet_ContigSet" 
      Tags="HGAP" 
      Version="2.3.0" 
      CreatedAt="2015-01-27T09:00:01" 
      xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
      xsi:schemaLocation="http://pacificbiosciences.com/PacBioDataModel.xsd">
      <pbbase:ExternalResources>
          <pbbase:ExternalResource 
              UniqueId="b095d0a3-94b8-4918-b3af-a3f81bbe529c" 
              TimeStampedName="contig_fasta_150304_231155"
              MetaType="PacBio.ContigFile.ContigFastaFile" 
              Name="First Contigs FASTA" 
              Description="Points to an example contigs FASTA file e.g. from HGAP." 
              ResourceId="file:///mnt/path/to/contigs.fasta" Tags="Example">
          </pbbase:ExternalResource>
      </pbbase:ExternalResources>
      <pbds:DataSetMetadata>
          <pbds:TotalLength>5000000</pbds:TotalLength>
          <pbds:NumRecords>500</pbds:NumRecords>
          <pbds:Contigs>
              <pbds:Contig 
                  Name="gi|229359445|emb|AM181176.4|" 
                  Description="Pseudomonas fluorescens SBW25 complete genome|quiver" 
                  Length="6722109" 
                  Digest="f627c795efad7ce0050ed42b942d408e"/>
          </pbds:Contigs>
      </pbds:DataSetMetadata>
  </pbds:ContigSet>
