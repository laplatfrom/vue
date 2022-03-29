<template>
  <CRow>
    <CCol :xs="6">
      <CCard class="mb-4">
        <CCardHeader>
          <strong>분석데이타입력</strong>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          <CButton color="primary" disabled>추론</CButton>
        </CCardHeader>
        <CCardBody>
          <CRow>
            <CCol :md="12">
              <CFormLabel for="inputTitle">Title</CFormLabel>
              <CFormInput id="inputTitle" type="email" />
            </CCol>
          </CRow>
          <CRow>
            <CCol :md="12">
              <CFormLabel for="inputContent">Content</CFormLabel>
              <CFormTextarea id="inputContent" rows="3" />
            </CCol>
          </CRow>
        </CCardBody>
      </CCard>
    </CCol>
    <CCol :xs="6">
      <CCard class="mb-4">
        <CCardHeader>
          <strong>분설결과</strong>
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          <CButton color="info" disabled>조회</CButton>
        </CCardHeader>
        <CCardBody>
          <CTable bordered>
            <CTableHead color="dark">
              <CTableRow>
                <CTableHeaderCell scope="col">우선순위</CTableHeaderCell>
                <CTableHeaderCell scope="col">대분류</CTableHeaderCell>
                <CTableHeaderCell scope="col">중분류</CTableHeaderCell>
                <CTableHeaderCell scope="col">소분류</CTableHeaderCell>
                <CTableHeaderCell scope="col">대표</CTableHeaderCell>
              </CTableRow>
            </CTableHead>
            <CTableBody>
              <CTableRow>
                <CTableHeaderCell scope="row">1</CTableHeaderCell>
                <CTableDataCell>직무</CTableDataCell>
                <CTableDataCell>보건</CTableDataCell>
                <CTableDataCell>보건</CTableDataCell>
                <CTableDataCell>
                  <div class="form-check">
                    <input
                      class="form-check-input"
                      id="flexCheckDefault2"
                      type="checkbox"
                    />
                  </div>
                </CTableDataCell>
              </CTableRow>
              <CTableRow>
                <CTableHeaderCell scope="row">2</CTableHeaderCell>
                <CTableDataCell>직무</CTableDataCell>
                <CTableDataCell>일반공공행정</CTableDataCell>
                <CTableDataCell>일반공공행정</CTableDataCell>
                <CTableDataCell>
                  <div class="form-check">
                    <input
                      class="form-check-input"
                      id="flexCheckDefault3"
                      type="checkbox"
                    />
                  </div>
                </CTableDataCell>
              </CTableRow>
              <CTableRow>
                <CTableHeaderCell scope="row">3</CTableHeaderCell>
                <CTableDataCell>직무</CTableDataCell>
                <CTableDataCell>공공질서</CTableDataCell>
                <CTableDataCell>공공질서</CTableDataCell>
                <CTableDataCell>
                  <div class="form-check">
                    <input
                      class="form-check-input"
                      id="flexCheckDefault"
                      type="checkbox"
                    />
                  </div>
                </CTableDataCell>
              </CTableRow>
            </CTableBody>
          </CTable>
        </CCardBody>
      </CCard>
    </CCol>
    <CCol :xs="6">
      <CCard class="mb-5">
        <CCardHeader>
          <strong>컨텐츠 부가정보</strong>
        </CCardHeader>
        <CCardBody>
          <CForm>
            <CRow class="mb-3">
              <CFormLabel for="inputEmail3" class="col-sm-2 col-form-label">
                초록
              </CFormLabel>
              <CCol sm="10">
                <CFormInput type="email" id="inputEmail3" />
              </CCol>
            </CRow>
            <CRow class="mb-3">
              <CFormLabel for="inputEmail3" class="col-sm-2 col-form-label">
                목차
              </CFormLabel>
              <CCol sm="10">
                <CFormInput type="email" id="inputEmail4" />
              </CCol>
            </CRow>
            <CRow class="mb-3">
              <CFormLabel for="inputEmail3" class="col-sm-2 col-form-label">
                저자
              </CFormLabel>
              <CCol sm="10">
                <CFormInput type="email" id="inputEmail4" />
              </CCol>
            </CRow>
            <CRow class="mb-3">
              <CFormLabel for="inputEmail3" class="col-sm-2 col-form-label">
                발행연도
              </CFormLabel>
              <CCol sm="10">
                <CFormInput type="email" id="inputEmail4" />
              </CCol>
            </CRow>
            <CRow class="mb-3">
              <CFormLabel for="inputEmail3" class="col-sm-2 col-form-label">
                발행일
              </CFormLabel>
              <CCol sm="10">
                <CFormInput type="email" id="inputEmail4" />
              </CCol>
            </CRow>
            <CRow class="mb-3">
              <CFormLabel for="inputEmail3" class="col-sm-2 col-form-label">
                등록기간
              </CFormLabel>
              <CCol sm="10">
                <CFormInput type="email" id="inputEmail4" />
              </CCol>
            </CRow>
          </CForm>
        </CCardBody>
      </CCard>
    </CCol>
  </CRow>
</template>
<script>
export default {
  name: 'Layout',
}
</script>
