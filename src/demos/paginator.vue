<template>
  <div>
    <c-row>
      <c-col>
        <c-paginator
          :query="{ $offset: 0, $limit: 2 }"
          :count="10"></c-paginator>
      </c-col>
    </c-row>
    <c-row>
      <c-col>
        <c-paginator
          :query="{ $offset: 4, $limit: 2 }"
          :count="10"></c-paginator>
      </c-col>
    </c-row>
    <c-row>
      <c-col>
        <c-paginator
          :query="{ $offset: 8, $limit: 2 }"
          :count="10"></c-paginator>
      </c-col>
    </c-row>
    <c-row>
      <c-col>
        <c-paginator
          :query="{ $offset: 10, $limit: 2 }"
          :count="10"></c-paginator>
      </c-col>
    </c-row>
    <c-row>
      <c-col>
        <c-paginator
          :query="{ $offset: 6, $limit: 2 }"
          :count="20"></c-paginator>
      </c-col>
    </c-row>
    <c-row>
      <c-col>
        <c-paginator
          :query="{ $offset: 16, $limit: 2 }"
          :count="20"></c-paginator>
      </c-col>
    </c-row>
    <c-row>
      <c-col>
        <c-paginator
          :query="{ $offset: 16, $limit: 2 }"
          :count="40"></c-paginator>
      </c-col>
    </c-row>
    <c-row>
      <c-col>
        <c-paginator
          :query="{ $offset: 26, $limit: 2 }"
          :count="40"></c-paginator>
      </c-col>
    </c-row>
  </div>
</template>

<script>
import CRow from 'components/c-row'
import CCol from 'components/c-col'
import CPaginator from 'components/c-paginator'

export default {
  components: {
    CRow,
    CCol,
    CPaginator
  }
}
</script>
